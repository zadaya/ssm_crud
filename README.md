# SSM_CRUD
一个基于SSM的学习小demo，用SpringMVC+Spring+Mybatis搭建的具有增删改查的学习案例

基本环境依赖
```
<!-- 引入项目依赖包 -->
<dependencies>
	<!-- Spring、Spring MVC -->
	<!-- spring web mvc -->
	<!-- https://mvnrepository.com/artifact/org.springframework/spring-webmvc -->
	<dependency>
		<groupId>org.springframework</groupId>
		<artifactId>spring-webmvc</artifactId>
		<version>4.3.7.RELEASE</version>
	</dependency>

	<!-- spring jdbc -->
	<!-- https://mvnrepository.com/artifact/org.springframework/spring-jdbc -->
	<dependency>
		<groupId>org.springframework</groupId>
		<artifactId>spring-jdbc</artifactId>
		<version>4.3.7.RELEASE</version>
	</dependency>

	<!-- spring-aspects 面向切面编程 -->
	<!-- https://mvnrepository.com/artifact/org.springframework/spring-aspects -->
	<dependency>
		<groupId>org.springframework</groupId>
		<artifactId>spring-aspects</artifactId>
		<version>4.3.7.RELEASE</version>
	</dependency>

	<!-- spring-text 单元测试模块 -->
	<!-- https://mvnrepository.com/artifact/org.springframework/spring-test -->
	<dependency>
		<groupId>org.springframework</groupId>
		<artifactId>spring-test</artifactId>
		<version>4.3.7.RELEASE</version>
		<scope>test</scope>
	</dependency>


	<!-- MyBatis -->
	<!-- https://mvnrepository.com/artifact/org.mybatis/mybatis -->
	<dependency>
		<groupId>org.mybatis</groupId>
		<artifactId>mybatis</artifactId>
		<version>3.4.2</version>
	</dependency>

	<!-- mybatis-spring MyBatis整合Spring的适配包 -->
	<!-- https://mvnrepository.com/artifact/org.mybatis/mybatis-spring -->
	<dependency>
		<groupId>org.mybatis</groupId>
		<artifactId>mybatis-spring</artifactId>
		<version>1.3.1</version>
	</dependency>

	<!-- 数据库连接池、驱动 -->
	<!-- https://mvnrepository.com/artifact/com.mchange/c3p0 -->
	<dependency>
		<groupId>com.mchange</groupId>
		<artifactId>c3p0</artifactId>
		<version>0.9.2</version>
	</dependency>
	<!-- https://mvnrepository.com/artifact/mysql/mysql-connector-java -->
	<dependency>
		<groupId>mysql</groupId>
		<artifactId>mysql-connector-java</artifactId>
		<version>8.0.22</version>
	</dependency>

	<!-- jstl、servlet-api、junit等常用包 -->
	<!-- https://mvnrepository.com/artifact/jstl/jstl -->
	<dependency>
		<groupId>jstl</groupId>
		<artifactId>jstl</artifactId>
		<version>1.2</version>
	</dependency>

	<!-- https://mvnrepository.com/artifact/javax.servlet/javax.servlet-api -->
	<dependency>
		<groupId>javax.servlet</groupId>
		<artifactId>javax.servlet-api</artifactId>
		<version>3.0.1</version>
		<scope>provided</scope>
	</dependency>

	<!-- https://mvnrepository.com/artifact/junit/junit -->
	<dependency>
		<groupId>junit</groupId>
		<artifactId>junit</artifactId>
		<version>4.12</version>
		<scope>test</scope>
	</dependency>

	<!-- MBG MyBatis 逆向工程生成代码的依赖包 -->
	<!-- https://mvnrepository.com/artifact/org.mybatis.generator/mybatis-generator-core -->
	<dependency>
		<groupId>org.mybatis.generator</groupId>
		<artifactId>mybatis-generator-core</artifactId>
		<version>1.3.5</version>
	</dependency>

	<!-- 分页插件 PageHelper -->
	<dependency>
		<groupId>com.github.pagehelper</groupId>
		<artifactId>pagehelper</artifactId>
		<version>5.0.0</version>
	</dependency>

	<!-- Jackson包，用于ResponseBody生成json数据 -->
	<!-- https://mvnrepository.com/artifact/com.fasterxml.jackson.core/jackson-databind -->
	<dependency>
		<groupId>com.fasterxml.jackson.core</groupId>
		<artifactId>jackson-databind</artifactId>
		<version>2.8.8</version>
	</dependency>

	<!-- JSR303 数据校验 ：tomcat7及以上版本支持 -->
	<!-- https://mvnrepository.com/artifact/org.hibernate/hibernate-validator -->
	<dependency>
		<groupId>org.hibernate</groupId>
		<artifactId>hibernate-validator</artifactId>
		<version>5.4.1.Final</version>
	</dependency>

	<!-- https://mvnrepository.com/artifact/commons-fileupload/commons-fileupload -->
	<dependency>
		<groupId>commons-fileupload</groupId>
		<artifactId>commons-fileupload</artifactId>
		<version>1.3.1</version>
	</dependency>

	<!-- https://mvnrepository.com/artifact/commons-beanutils/commons-beanutils -->
	<dependency>
		<groupId>commons-beanutils</groupId>
		<artifactId>commons-beanutils</artifactId>
		<version>1.9.3</version>
	</dependency>

</dependencies>
```
