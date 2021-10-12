# spring boot + kotiln + docker

코틀린 스프링부트 샘플앱을 도커로 실행하는 테스트 진행
(mariadb 사용)

## 실행

### 1. 앱 빌드
`$ ./gradlew build -x test #테스트 제외`

### 2. 도커 실행 (app+mariadb)
`$ docker-compose up --build`

## 참고

- [Building web applications with Spring Boot and Kotlin](https://spring.io/guides/tutorials/spring-boot-kotlin/)
- [Spring Boot with Docker](https://spring.io/guides/gs/spring-boot-docker/)