FROM registry.eazybuilder-devops.cn/library/baseos:jdk8

WORKDIR /opt/sql-validate
COPY config/  /opt/sql-validate/config/
ADD sql-validate*.jar /opt/sql-validate/sql-validate.jar

ENV JAVA_OPTS="-Xmx512g"
CMD java $JAVA_OPTS -jar sql-validate.jar
