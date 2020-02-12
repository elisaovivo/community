## IT社区

## 资料
[Spring文档](https://spring.io/guides)
[Bootstrap](https://v3.bootcss.com/getting-started/)
[Github OAuth](https://developer.github.com/apps/building-oauth-apps/)
[Spring](https://docs.spring.io/spring-boot/docs/current/reference/html/spring-boot-features.html)
## 工具
[Git](https://git-scm.com/)
[visual-paradigm](https://www.visual-paradigm.com)

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