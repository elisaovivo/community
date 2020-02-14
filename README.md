## IT社区

## 资料
[Spring文档](https://spring.io/guides)
[Bootstrap](https://v3.bootcss.com/getting-started/)
[Github OAuth](https://developer.github.com/apps/building-oauth-apps/)
[Spring](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/#boot-features-embedded-database-support)
## 工具
[Git](https://git-scm.com/)
[visual-paradigm](https://www.visual-paradigm.com)
[Flyway](https://flywaydb.org/getstarted/firststeps/maven)
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