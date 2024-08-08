## 쿠버네티스를 활용한 무중단 MSA 서비스 배포 플랫폼
개발자들이 편하게 쿠버네티스를 이용해서 무중단배포를 이용할 수 있는 Paas 플랫폼

https://github.com/user-attachments/assets/50658090-af8b-4099-b61f-ceced665621d

### 개발 환경
`JAVA` == 17
`Spring Boot` == 3.0.8

## 서비스 흐름도
<img width="499" alt="서비스 흐름도" src="https://github.com/user-attachments/assets/2b0b6a2b-80c9-4e24-a00f-099c5183c6b0">

## 아키텍쳐 다이어그램
![아키텍처_다이어그램 drawio](https://github.com/user-attachments/assets/3dc85e45-34bc-4e9d-b0b8-544f4faf010e)

### Building the project
Clone the project
```
$ git clone <Repository-URL>
```

Build
```
$ chmod +x ./gradlew
$ ./gradlew build
```

Run
```
$ cd build/libs/
$ java -jar ait-0.0.1-SNAPSHOT.jar
```
