FROM apache/seata-server:2.2.0

RUN wget https://gitee.com/icodegarden/resources/blob/master/download/mysql-connector-java-5.1.42.jar
RUN wget https://gitee.com/icodegarden/resources/blob/master/download/mysql-connector-java-8.0.27.jar

RUN mkdir -p /seata-server/libs/jdbc

RUN mv mysql-connector-java-5.1.42.jar /seata-server/libs
RUN mv mysql-connector-java-5.1.42.jar /seata-server/libs/jdbc
RUN mv mysql-connector-java-8.0.27.jar /seata-server/libs/jdbc

MAINTAINER xff
