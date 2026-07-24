<div align="center">

<h1>Java · Spring Backend Developer</h1>

<h3>문제가 발생한 이유를 찾고 직접 검증하며 개선하는 과정을 좋아합니다.</h3>

<p>Java와 Spring을 중심으로 백엔드 개발을 공부하고 있습니다.</p>

<a href="https://guseoh.github.io/">
  <img src="https://img.shields.io/badge/Tech_Blog-181717?style=for-the-badge&logo=github&logoColor=white" alt="Tech Blog"/>
</a>

</div>

<br>

## 🛠 Tech Stack

### Backend

<p>
  <img height="28" src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
  <img height="28" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img height="28" src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security"/>
  <img height="28" src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring Data JPA"/>
  <img height="28" src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white" alt="Hibernate"/>
  <img height="28" src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white" alt="Thymeleaf"/>
  <img height="28" src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white" alt="Gradle"/>
  <img height="28" src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit 5"/>
</p>

### Database & Infrastructure

<p>
  <img height="28" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"/>
  <img height="28" src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white" alt="Flyway"/>
  <img height="28" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img height="28" src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Compose"/>
  <img height="28" src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="Amazon AWS"/>
  <img height="28" src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx"/>
  <img height="28" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
  <img height="28" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
</p>

### Frontend & Blog

<p>
  <img height="28" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img height="28" src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"/>
  <img height="28" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img height="28" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img height="28" src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white" alt="Astro"/>
</p>

### Tools

<p>
  <img height="28" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img height="28" src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  <img height="28" src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white" alt="Notion"/>
</p>

<br>

## 📌 Projects

<details>
<summary><strong>Board — 개발자 커뮤니티</strong></summary>

<br>

Spring Boot MVC와 Thymeleaf 기반의 커뮤니티 프로젝트입니다.

- 게시글·댓글, 세션 로그인과 OAuth2 인증·인가 구현
- 원자적 UPDATE를 활용한 조회수 동시성 문제 개선
- AWS EC2·RDS 배포와 GitHub Actions 기반 CI/CD 구성
- **Tech:** Java 17, Spring Boot, Spring Security, Spring Data JPA, Thymeleaf, MySQL, AWS
- **Repository:** [guseoh/board](https://github.com/guseoh/board)

</details>

<details>
<summary><strong>PawCycle Commerce — 반려동물 소모품 이커머스</strong></summary>

<br>

개와 고양이용 소모품의 일반 구매와 정기배송을 지원하는 이커머스 프로젝트입니다.

- 공개 상품 탐색부터 세션 로그인, 구독 생성·조회까지 1차 수직 MVP 구현
- Spring Security의 세션·CSRF 보호와 인증 회원 기반 소유권 검증 적용
- Flyway 스키마 관리와 Docker Compose·Nginx 로컬 통합 환경 구성
- **Tech:** Java, Spring Boot, Spring Security, JPA, MySQL, Flyway, Next.js, Docker
- **Repository:** [guseoh/pawcycle-commerce](https://github.com/guseoh/pawcycle-commerce)

</details>

<details>
<summary><strong>Mini Tomcat — HTTP 서버·서블릿 컨테이너 학습</strong></summary>

<br>

Java 표준 라이브러리만으로 HTTP 서버와 Servlet Container의 책임을 단계별로 구현하는 학습 프로젝트입니다.

- Java 17·Gradle 기반 프로젝트와 JUnit·AssertJ 테스트 환경 구성
- 서버 설정과 애플리케이션 생명주기를 표현하는 Stage 0 기반 구현
- TCP 연결부터 HTTP 파싱과 Servlet 처리 구조까지 단계별 학습 예정
- **Tech:** Java 17, Gradle, JUnit 5, AssertJ
- **Repository:** [guseoh/mini-tomcat](https://github.com/guseoh/mini-tomcat)

</details>

<details>
<summary><strong>Tech Blog — 개발 학습과 트러블슈팅 기록</strong></summary>

<br>

Java·Spring·JPA·HTTP·네트워크·인프라를 학습하고 검증한 내용을 기록하는 기술 블로그입니다.

- Markdown 기반 콘텐츠와 Book·Series·Category 탐색 구조 구성
- 본문 검색, RSS, sitemap, SEO와 라이트·다크 모드 지원
- GitHub Actions와 GitHub Pages 기반 자동 검증·배포 구성
- **Tech:** Astro, TypeScript, Markdown, GitHub Actions, GitHub Pages
- **Site:** [guseoh.github.io](https://guseoh.github.io/)
- **Repository:** [guseoh/guseoh.github.io](https://github.com/guseoh/guseoh.github.io)

</details>

<br>

## 🐾 GitAnimals

<div align="center">

<a href="https://www.gitanimals.org/">
  <img
    src="https://render.gitanimals.org/farms/guseoh"
    width="600"
    alt="GitAnimals Farm"
  />
</a>

</div>

<!--
학력이나 자격증을 공개하고 싶을 때만 아래 주석을 해제하세요.

## 🎓 Education & Certifications

- 학력:
- 자격증:
-->
