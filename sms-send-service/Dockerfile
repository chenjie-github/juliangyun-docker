FROM         registry.cn-shanghai.aliyuncs.com/wuzhiyun/base-java:1.0
MAINTAINER   ChenJie (chenjie@wuzhiyun.com)

#把java与tomcat添加到容器中
COPY sms-send-service /home/sms-send-service

VOLUME ["/home"]

RUN /home/sms-send-service/bin/Start restart
