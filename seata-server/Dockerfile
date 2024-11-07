FROM apache/seata-server:2.2.0

#RUN wget https://gitee.com/icodegarden/resources/blob/master/download/mysql-connector-java-5.1.42.jar
RUN wget https://gitee.com/icodegarden/resources/blob/master/download/mysql-connector-java-8.0.27.jar

#RUN mv mysql-connector-java-5.1.42.jar /seata-server/libs
RUN mv mysql-connector-java-8.0.27.jar /seata-server/lib

# set extra environment
ENV LOADER_PATH="/seata-server/lib"
ENV TZ="Asia/Shanghai"
CMD ["bash","-c","/seata-server/bin/seata-server.sh && tail -f /dev/null"]

MAINTAINER xff
