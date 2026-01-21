# EarthWith Backend

환경 보호 커뮤니티 플랫폼 백엔드 서버

## 기술 스택

- Java 17
- Spring Boot 3.x
- Spring Security + JWT
- MyBatis
- MySQL
- AWS S3

## 주요 기능

- 회원 인증/인가 (JWT)
- 게시판 CRUD
- 댓글 시스템
- 북마크
- 관리자 기능
- 뉴스 API 연동 (Naver)
- 파일 업로드 (S3)

## 실행 방법

```bash
./gradlew bootRun
```

## 환경 변수

```
JWT_SECRET=your_jwt_secret
NAVER_CLIENT_ID=your_client_id
NAVER_CLIENT_SECRET=your_client_secret
DB_PASSWORD=your_db_password
```

## 관련 저장소

- Frontend: [earthwith-frontend](https://github.com/wookidoki/earthwith-frontend)
