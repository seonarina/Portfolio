# Portfolio - Photogram  π·β€οΈπ

- νμ¬ κ°μ₯ μΈκΈ° μλ μμ λ―Έλμ΄ νλ«νΌ μ€ νλμΈ μΈμ€νκ·Έλ¨μ ν΄λ‘  μ½λ©ν ν¬ν κ·Έλ¨μλλ€. 
- μ¬μ§μ μλ‘λνκ³ , κ΅¬λνκΈ° κΈ°λ₯μ ν΅ν΄ κ²μλ¬Όμ κ³΅μ ν  μ μμ΅λλ€. μλ‘λλ κ²μλ¬Όμ 'μ’μμ'λ₯Ό λλ₯΄κ±°λ, λκΈμ μμ±νλ©° μ¬μ©μλ€λΌλ¦¬ μν΅ν  μ μλ μμ λ€νΈμν¬ νλ«νΌμλλ€.
 - [ν¬ν κ·Έλ¨ PDFλ‘ λ³΄κΈ°](https://github.com/seonarina/Portfolio/blob/main/portfolio_photogram.pdf)

## [STS ν΄μ μΈννκΈ° - νλ¬κ·ΈμΈ μ€μ ]

- https://blog.naver.com/getinthere/222322821611

## [μμ‘΄μ±]

- Sring Boot DevTools

- Lombok

- Spring Data JPA

- MariaDB Driver

- Spring Security

- Spring Web

- oauth2-client

```xml

<!-- μνλ¦¬ν° νκ·Έ λΌμ΄λΈλ¬λ¦¬ -->

<dependency>

<groupId>org.springframework.security</groupId>

<artifactId>spring-security-taglibs</artifactId>

</dependency>

<!-- JSP ννλ¦Ώ μμ§ -->

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

## [νκ·Έ λΌμ΄λΈλ¬λ¦¬]

```sql

create user 'cos'@'%' identified by 'cos1234';

GRANT ALL PRIVILEGES ON *.* TO 'cos'@'%';

create database photogram;

```

## [yml μ€μ ]

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

## [νκ·Έ λΌμ΄λΈλ¬λ¦¬]

```jsp

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core"%>

<%@ taglib prefix="sec" uri="http://www.springframework.org/security/tags"%>

```
μΆμ²-https://github.com/codingspecialist/EaszUp-Springboot-Photogram-Start


## [κ°λ° νκ²½]

<h3>Platforms & Languages & Tools</h3>

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=Spring Boot&logoColor=white"/>  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/> <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/>  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/Json-000000?style=flat-square&logo=Json&logoColor=white"/>  
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=Oracle&logoColor=white"/> <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=MariaDB&logoColor=white"/>
<img src="https://img.shields.io/badge/Eclipse-2C2255?style=flat-square&logo=Eclipse&logoColor=white"/> <img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/> <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/> <img src="https://img.shields.io/badge/DBeaver-F47D31?style=flat-square&logo=DBeaver&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-black?style=flat&logo=GitHub&logoColor=#181717"/>
