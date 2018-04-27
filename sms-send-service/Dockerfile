FROM         centos:7
MAINTAINER   ChenJie (chenjie@wuzhiyun.com)

#把java与tomcat添加到容器中
COPY jdk1.8.0_171 /usr/local/java/jdk1.8.0_171

#配置java与tomcat环境变量
ENV JAVA_HOME /usr/local/java/jdk1.8.0_171
ENV CLASSPATH $JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
ENV PATH $PATH:$JAVA_HOME/bin

VOLUME ["/home"]
