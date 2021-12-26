FROM mysql:5.7
MAINTAINER Lizhuyou
User root
WORKDIR /opt
ENV MYSQL_ROOT_PASSWORD=123456
ENV TZ=Asia/Shanghai
RUN sed -i 's/bind-address/#bind-address/g' /etc/mysql/mysql.conf.d/mysqld.cnf
VOLUME ["/data/mysql:/var/lib/mysql"]
EXPOSE 3306


