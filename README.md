## IT社区

## 资料
[Spring文档](https://spring.io/guides)
[Bootstrap](https://v3.bootcss.com/getting-started/)
[Github OAuth](https://developer.github.com/apps/building-oauth-apps/)
[Spring](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/#boot-features-embedded-database-support)
[Thymeleaf](https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html#setting-attribute-values)
[菜鸟教程](https://www.runoob.com/mysql/mysql-insert-query.html) 
[Spring Dev Tool](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/#using-boot-devtools)
## 工具
[Git](https://git-scm.com/)
[visual-paradigm](https://www.visual-paradigm.com)
[Flyway](https://flywaydb.org/getstarted/firststeps/maven)
[Lombok](https://projectlombok.org/setup/maven)
[Live Reload](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei/related) 
## 脚本
```sql
create table USER
(
	ID INT auto_increment,
	NAME VARCHAR(50),
	ACCOUNT_ID VARCHAR(50),
	TOKEN CHAR(36),
	GMT_CREATE BIGINT,
	GMT_MODIFIED BIGINT,
	constraint USER_PK
		primary key (ID)
);

```

```bash
mvn flyway:migrate
```