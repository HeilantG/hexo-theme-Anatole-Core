---
title: oracle
date: 2020-09-22 15:51:17
tags: Oracle
---

# Oracle

建立用户:

```sql
create user {username} identified by {password};
```

给与权限:

```sql
grant dba to {username};
```

查询此用户下属的表:

```sql
select * from all_tables where owner='{username}';
```

 查看当前登录的用户的表:

```sql
select table_name from user_tables;
```

username为用户名，用户名必须是大写。

