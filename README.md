## opzpy123的java社区

## 快速运行
1. 安装必备工具  
````
JDK，Maven
````
2. 克隆代码到本地
````
git clone
````

3. 修改数据库配置文件
````
spring.datasource.username=root
spring.datasource.password=111
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/datasource_table?useUnicode=true&characterEncoding=utf8&useSSL=false&serverTimezone= Asia/Shanghai 
spring.datasource.type=com.alibaba.druid.pool.DruidDataSource
````
4. 运行打包命令
````
mvn package
````
5. 运行项目  
````
java -jar target/mypeojectdemo-0.0.1-SNAPSHOT.jar
````
6. 访问项目
````
http://localhost:8080
````


## 资料
[Spring 文档](https://spring.io/guides)    
[Spring Web](https://spring.io/guides/gs/serving-web-content/)   
[Github deploy key](https://developer.github.com/v3/guides/managing-deploy-keys/#deploy-keys)    
[Bootstrap](https://v3.bootcss.com/getting-started/)    
[Spring](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/#boot-features-embedded-database-support)    
[菜鸟教程](https://www.runoob.com/mysql/mysql-insert-query.html)    
[Thymeleaf](https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html#setting-attribute-values)    
[Spring Dev Tool](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/#using-boot-devtools)  
[Spring MVC](https://docs.spring.io/spring/docs/5.0.3.RELEASE/spring-framework-reference/web.html#mvc-handlermapping-interceptor)  
[Markdown 插件](http://editor.md.ipandao.com/)   
[UFfile SDK](https://github.com/ucloud/ufile-sdk-java)  

## 工具
[Git](https://git-scm.com/download)   
[Lombok](https://www.projectlombok.org)     
[Postman](https://chrome.google.com/webstore/detail/coohjcphdfgbiolnekdpbcijmhambjff)

## 脚本
````
sql_建表

CREATE TABLE `user` (
  `id` bigint(32) NOT NULL AUTO_INCREMENT,
  `username` varchar(255) DEFAULT NULL,
  `password` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=0 DEFAULT CHARSET=utf8
````

## 更新日志
