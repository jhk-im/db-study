# Database란?

## What is a database?

### 데이터 컬렉션

* 진료 기록, To do List, 장바구니, 전화번호부 등
* 전화번호부에서 성이 김씨인 사람을 모두 찾아야 한다면?
* 특정 지역 번호의 전화번호를 모두 찾아야 하는 경우라면?

>단순 데이터 컬렉션이 아니라 해당 데이터를 액세스하고 조작하는 메소드를 포함하고 있어야 한다.(인터페이스)

### `Database` vs `Database Managemnet System`

* 데이터, 데이터 컬렉션을 갖고 있는 것과 데이터에 관한 인터페이스를 갖고있는 것은 별개
* `App` -> `DBMS` -> `Database`
* DBMS를 통해 데이터베이스와 인터페이스 할 수 있음
* DBMS = PostgreSQL, MySQL, SQLite, Oracle Database 등

>데이터베이스란? 액세스 가능한 인터페이스를 가진 컴퓨팅 데이터의 구조화된 집합이다.

### `SQL` vs `MySQL`

#### SQL

* 구조화 쿼리 언어(Structured Query Language)
* 데이터베이스에 말을 걸 때 사용하는 언어
* 데이터와 상호작용(접근, 업데이트, 삭제 등)

```sql
--Find All Users Who Are 18 Or Older
SELECT * FROM Users WHERE Age >= 18;
```

> MySQL로 작업할 때 SQL을 항상 사용하고 있다. 관계형 데이터베이스(RDBMS)는 SQL을 사용한다. 각각의 RDBMS 마다 SQL 표준을 가지고 있으며 문법상 약간 다를 수 있지만 대부분 굉장히 유사하다. SQL을 공부하였다면 다른 RDBMS로의 전환은 크게 어렵지 않다. RDBMS의 유니크 함은 SQL언어 자체가 아니라 각자 제공하는 기능에 달려있다.

[MAC에서 MySQL + Workbench 설치](https://velog.io/@kms9887/mysql-%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C-workbench)
