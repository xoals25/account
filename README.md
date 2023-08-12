# account RESTful API

### 기술 스택
- 언어: Java
- 프레임 워크: SpringBoot
- 데이터 베이스: H2, Redis
- 테스트: Junit5, Mockito

### 주요 기능
- Redis의 Redisson Lock을 활용하여 동시성을 제어 하여 중복 거래 방지 처리
- 계좌 생성, 계좌 해지, 계좌 확인, 잔액 사용, 잔액 사용 취소, 잔액 사용 확인

### ERD
![account erd](https://github.com/xoals25/account/assets/68364917/a08b5857-4c23-435c-92cf-52c2b2e49a9d)
