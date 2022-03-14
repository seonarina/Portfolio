# Portfolio - Photogram  📷❤️👍

- 현재 가장 인기 있는 소셜 미디어 플랫폼 중 하나인 인스타그램을 클론 코딩한 포토그램입니다. 
- 사진을 업로드하고, 구독하기 기능을 통해 게시물을 공유할 수 있습니다. 업로드된 게시물에 '좋아요'를 누르거나, 댓글을 작성하며 사용자들끼리 소통할 수 있는 소셜 네트워크 플랫폼입니다.
 - [포토그램 PDF로 보기](https://github.com/seonarina/Portfolio/blob/main/portfolio_photogram.pdf)

## [STS 툴에 세팅하기 - 플러그인 설정]

- https://blog.naver.com/getinthere/222322821611

## [의존성]

- Sring Boot DevTools

- Lombok

- Spring Data JPA

- MariaDB Driver

- Spring Security

- Spring Web

- oauth2-client

```xml

<!-- 시큐리티 태그 라이브러리 -->

<dependency>

<groupId>org.springframework.security</groupId>

<artifactId>spring-security-taglibs</artifactId>

</dependency>

<!-- JSP 템플릿 엔진 -->

<dependency>

<groupId>org.apache.tomcat</groupId>

<artifactId>tomcat-jasper</artifactId>

<version>9.0.43</version>

</dependency>

<!-- JSTL -->

<dependency>

<groupId>javax.servlet</groupId>

<artifactId>jstl</artifactId>

</dependency>

```

## [태그 라이브러리]

```sql

create user 'cos'@'%' identified by 'cos1234';

GRANT ALL PRIVILEGES ON *.* TO 'cos'@'%';

create database photogram;

```

## [yml 설정]

```yml

server:

port: 8080

servlet:

context-path: /

encoding:

charset: utf-8

enabled: true

spring:

mvc:

view:

prefix: /WEB-INF/views/

suffix: .jsp

datasource:

driver-class-name: org.mariadb.jdbc.Driver

url: jdbc:mariadb://localhost:3306/cos?serverTimezone=Asia/Seoul

username: cos

password: cos1234

jpa:

open-in-view: true

hibernate:

ddl-auto: update

naming:

physical-strategy: org.hibernate.boot.model.naming.PhysicalNamingStrategyStandardImpl

show-sql: true

servlet:

multipart:

enabled: true

max-file-size: 2MB

security:

user:

name: test

password: 1234

file:

path: C:/src/springbootwork-sts/upload/

```

## [태그 라이브러리]

```jsp

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core"%>

<%@ taglib prefix="sec" uri="http://www.springframework.org/security/tags"%>

```
출처-https://github.com/codingspecialist/EaszUp-Springboot-Photogram-Start


## [개발 환경]

<h3>Platforms & Languages & Tools</h3>

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=Spring Boot&logoColor=white"/>  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/> <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/>  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/Json-000000?style=flat-square&logo=Json&logoColor=white"/>  
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=Oracle&logoColor=white"/> <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=MariaDB&logoColor=white"/>
<img src="https://img.shields.io/badge/Eclipse-2C2255?style=flat-square&logo=Eclipse&logoColor=white"/> <img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/> <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/> <img src="https://img.shields.io/badge/DBeaver-F47D31?style=flat-square&logo=DBeaver&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-black?style=flat&logo=GitHub&logoColor=#181717"/>
