SOLAlchemy
- 
- 내부의 SQL 특이성과 데이터베이스로부터 코드를 추상화해준다. 
- DB 혹은 Data warehouse 사이의 마이그레이션을 쉽게해주며, 종속성을 완화해준다.

SOLAlchemy를 조작하는 2가지 방법
-
- SQL Expression Language: 전통적인 스키마 중심의 SQL 방식
- ORM: domain-driven에 집중할 수 있는 방식

create_engine() 옵션
-
- echo: 로깅
- encoding: 인코딩
- isolation_level: READ_COMMITED, AUTOCOMMIT 등의 옵션 제공
- pool_recycle: 일정시간이 지난 pool을 이용하지 않도록 도와준다. 엔진과 무관한 Pool의 옵(MySQL은 8시간의 디폴트값을 가지므로, 이 옵션이 매우 유용히 사용된다.)
