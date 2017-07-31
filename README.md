# eureka-service

该项目基于zk做配置中心创建的eureka注册服务，实际使用可以打成jar 直接运行

java -jar eureka-server-0.0.1-SNAPSHOT.jar --spring.config.location=F:\javaExam\bootstrap-release.yml

 其中：--spring.config.location=F:\javaExam\bootstrap-release.yml是配置文件路径，在启动jar时会读取这个配置文件，实现了动态配置
 
运行改项目需要先启动zk