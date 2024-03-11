# Guestbook-Clone
Implementation of a clone of Guestbook from the [book(코드로 배우는 스프링 부트 웹 프로젝트)](https://m.yes24.com/Goods/Detail/96051853) and the [Github(zk2840174/sboot_ch04)](https://github.com/zk2840174/sboot_ch04/tree/main).

This project uses the [Udacity Nanoderee Style](https://udacity.github.io/git-styleguide/) as a git commit message rule.

## Technical Stack

- Language
  - Java 17.0.10
  - HTML
- Framework
  - Spring boot 3.2.2
- Template Engine
  - Thymeleaf
- Database
  - MySQL
- ORM
  - JPA
  - querydsl
- Test
  - JUnit

## Run Application with IntelliJ

1. Git clone repository

```
git clone https://github.com/juintination/Guestbook-Clone.git
```

2. Open Project with IntelliJ

Select `build.gradle` in the guestbook directory and `Open as Project`

3. Modify application.properties

Modify the `application.properties` file to suit your DB environment.

4. Run the application

Run `GuestbookApplication.java` and go to `localhost:8080/guestbook/`
