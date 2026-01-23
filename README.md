# Kafka Project [readme 임시]

구독, 비동기, Kafka 사용방법 등 프로젝트

Kafka는 Docker를 통해서 생성하고, 주키퍼는 따로 사용하지 않는다.<br/>
- 간단한 docker compose 사용방법 정리, Kafka 주키퍼 따로 사용하지 않는 이유 정리 추가 예정

## 프로젝트 간단정리 [ 임시 ]

1. Producer 프로젝트 1 <br/>
2. Consumer 프로젝트 2 <br/>
<br/>
Producer 프로젝트는 mysql, Consumer 프로젝트는 mongoDB 사용으로 mysql -> mongodb로 카프카를 활용

## Docker 로컬 세팅
Docker Desktop || colima <br/>
- Docker Desktop은 UI 활용으로 인한 편하게 사용이 가능.
- colima Docker CLI 그대로 사용이 가능하고 가볍고 빠른편에 속함.
<br/>
해당 프로젝트에서는 colima 채택해서 Docker 환경 구축 후 프로젝트 추가 작업 진행예정.


## DB 세팅
Producer 프로젝트는 mysql 또는 mariadb 사용<br/>
Consumer 프로젝트는 mongodb 사용.<br/>
 
