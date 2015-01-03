weidu-spring
============
创新型项目,希望有志之士加入
============
注意事项:
1.maven项目:
如果有jar包需要引入必须在网站http://mvnrepository.com/
找到依赖包,具体如下,例如:如果需要mysql连接的Java依赖包;查找得到xml代码段:
-------------------------------------
================================
<dependency>
	<groupId>mysql</groupId>
	<artifactId>mysql-connector-java</artifactId>
	<version>5.1.34</version>
</dependency>
=================================
---------------------------------------
放入到pom.xml中,并加以说明
2.目录结构说明:
src目录分为main 和test
main 又分为:
--java :idea
   --action:主要写controller与外部交互
   --dao主要写接口
   --service实现接口
   --util主要是工具类
   --module主要用来写实体类
resource--主要用于配置文件存放
webapp -- 网页部分和web的配置
---------------------
test专门做单元测试用:编写的代码一定要进行单元测试.web的程序一定要做单元测试