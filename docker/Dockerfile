FROM yanzhengui/java:8

MAINTAINER kea_iv@qq.com
ADD target/demo-0.0.1-SNAPSHOT.jar /app.jar

EXPOSE 8888
ENTRYPOINT ["java","-Xmx300m","-Dserver.port=8888","-jar","app.jar"]