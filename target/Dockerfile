# 基于java镜像创建新镜像
FROM java:8
# 作者
MAINTAINER huangxinjun
# 将jar包添加到容器中并更名为app.jar
ADD demo-0.0.1-SNAPSHOT.jar /root/docker_test/app.jar
EXPOSE 8091
# 运行jar包
ENTRYPOINT ["java","-jar","/root/docker_test/app.jar"]
