# SpringBlog from Millky

밀키(millky.com)에서 블로그 부분을 뽑아(?) 오픈소스 합니다.
http://millky.com/@origoni

단지 코드만 공개한는 것이 아니라. 개발 과정을 같이 공개하려 합니다.

### DEMO
- http://blog.millky.com/post/list

- 해당코드 수정없이(appSecret 제외) 사용합니다.
- 어떠한 정보도 기록하지 않습니다.
- 많은 테스트 부탁드립니다.

### 관련 링크
- http://millky.com/
- http://millky.com/@origoni/folder/30/post/list

### Project Convention


#### Environment
- Java version: 8 Update 45
- Spring Boot version: 1.2.5
- Maven version: 3.3.3
- Lombok version: 1.16.4
- Default Encoding: UTF-8
- Default SCM : git

#### Package Structure

```
com.millky.blog
    └── application
        └── configuration
        └── utility
    └── domain
        └── model
            └── command
            └── entity
        └── repository
        └── service
    └── infrastructure
        └── dao
    └── presentation
        └── controller
            └── rest
        └── support
            └── result
```

#### 프로젝트 설정
1. STS 설치 -> http://millky.com/@origoni/post/1100
2. Lombok 설치 -> https://projectlombok.org/ (설치 : http://millky.com/@origoni/post/1164)
3. GitHub 에서 다운 -> http://millky.com/@origoni/post/1145 (OSX : http://millky.com/@origoni/post/1140)

