<img src="https://capsule-render.vercel.app/api?type=slice&color=6FC7E1&height=220&section=header&text=Han%20Sangbeom&fontSize=56&fontColor=000000&desc=Backend%20Developer&descAlignY=72" />

### 안녕하세요, 한상범입니다 👋

문제를 끝까지 해결하고, 안정적으로 동작하는 기능을 책임감 있게 완성하는 **백엔드 개발자**입니다.
인증·인가와 배포 과정에서 만난 문제(CORS, 토큰 검증 등)를 직접 해결하며 서비스 전체 흐름을 이해해 가고 있습니다.

- 🔭 Spring Security Filter 기반 JWT 인증 구조와 Refresh Token 적용 중
- 🌱 테스트 코드 작성, 배포·운영(AWS) 학습 중
- 📫 sidaumv@gmail.com · [Notion 포트폴리오](https://www.notion.so/151acedd62ff803a90d3dbf771b500cd)

<br>

### 🛠 Tech Stack

**Main**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-555555?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Also used**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)

<br>

### 📌 Projects

| 프로젝트 | 설명 | 기술 | 링크 |
|---|---|---|---|
| **JWT 인증 게시판** | 로그인 시 JWT 발급, 작성자만 수정·삭제 가능한 게시판. Vercel·Render로 배포 | Spring Boot, Spring Security, JPA, MySQL, React | [Demo](https://boardspring.vercel.app/) · [Repo](https://github.com/magnoria/저장소이름) |
| **DevConnect** (팀, 5명) | 프리랜서 개발자와 기업을 연결하는 중개 플랫폼. 기업 로그인·목록 API, JWT 발급 및 Redis 저장 담당 | Spring Boot, MySQL, Redis, Flutter | [Repo](https://github.com/magnoria/저장소이름) |
| **호텔 관리 플랫폼** (팀) | 지점별 객실·예약·직원·매출을 한눈에 보는 관리자 시스템. 메인 대시보드와 지점 관리 담당 | Spring Boot, MySQL, React | [Repo](https://github.com/magnoria/저장소이름) |

<br>

### 🔧 Troubleshooting

- **CORS preflight 차단**: Vercel과 Render의 도메인이 달라 OPTIONS 요청이 막힘 → `allowedOrigins`·`allowedMethods` 설정과 Security `cors()` 활성화로 해결
- **작성자 버튼 미표시**: localStorage 사용자 정보와 게시글 작성자 필드명 불일치 → `userId` 기준으로 구조를 통일해 해결

<br>

<sub>수만 가지의 나뭇가지에서 하나를 골라 걸어가고 있습니다 🌙</sub>
