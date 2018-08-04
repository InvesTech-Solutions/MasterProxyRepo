FROM mysql:5.7.22

MAINTAINER me

COPY . .

ENV MYSQL_ROOT_PASSWORD='newpass'
ENV MYSQL_DATABASE='recommendedStocks'

ADD data/schema.sql /docker-entrypoint-initdb.d

EXPOSE 3306
