## Main Differences between MongoDB and MySQL

#### MySQL
MySQL은 관계형 데이터베이스(RDBMS)이다. tables와 rows 로 데이터를 저장하며 Structured Query Language(SQL)를 이용하여 데이터에 접근한다.

데이터베이스 스키마와 데이터 모델이 미리 정의되어있어야 하며, 데이터는 반드시 이 스키마에 match 되어 저장되어야 한다. 이러한 엄격함은 '안전함'이라는 장점을 갖으나 한편 '유연성이 떨어진다' 라는 한계를 갖는다.

새로운 타입이나 포맷의 데이터가 DB에 저장되기 위해서는 schema migration이 반드시 수반되어야 하며, 이것은 DB가 크면 클수록 굉장히 복잡하고 expensive 한 작업이 된다.

#### MongoDB
전통적인 관계형 데이터베이스와는 다르게, non-relational (or NoSQL)적인 특징을 갖는다. table과 row 같이 스키마가 고정된 구조 대신, JSON형태의 동적 스키마형 문서를 사용한다.

몽고디비 documents 는 일련의 키와 밸류의 쌍으로 이루어져있다.

## When to Use MongoDB vs MySQL
flexibility 는 몽고디비의 가장 큰 장점이며,
엄격하고 안정적인 운영은 MySQL의 강점이다.