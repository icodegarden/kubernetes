FROM apache/seata-server:2.2.0

RUN wget https://gitee.com/icodegarden/resources/blob/master/download/mysql-connector-j-8.0.33.jar

#jdbc默认不存在需要创建
#RUN mkdir -p /seata-server/lib/jdbc

RUN mv mysql-connector-j-8.0.33.jar /seata-server/libs

RUN ls /seata-server/libs

MAINTAINER xff
