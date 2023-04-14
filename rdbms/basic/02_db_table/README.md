# DB & Table

## 데이터 베이스 생성하기

```txt
Database Server
[Dog Walker DB][Soap Shop DB]
[Practice DB][News Site DB]

[Dog Walker DB]
- Dogs
- Users*
- Payments*

[Soap Shop DB]
- Soaps
- Users*
- Payments*

* 구동 중인 MySQL 서버 내부에서 벽으로 둘러싼 개별 데이터베이스를 만드는 방법

mysql.server start
mysql -u root -p
```

```sql
show databases;

CREATE DATABASE soap_store;
CREATE DATABASE dog_app;
```

The general command for creating a database:
`CREATE DATABASE <database_name>;`

A specific example: `CREATE DATABASE soap_store;`

### Table
