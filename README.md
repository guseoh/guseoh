<div align="center">

# guseoh

**Java · Spring Backend Developer**

Java와 Spring을 중심으로 백엔드 개발과 시스템 설계를 공부하고 있습니다.  
문제를 재현하고, 코드와 테스트·측정 결과를 바탕으로 개선하는 과정을 중요하게 생각합니다.

<a href="https://guseoh.github.io/"><img src="https://img.shields.io/badge/Tech_Blog-24292F?style=flat-square&amp;logo=github&amp;logoColor=white" alt="Tech Blog" height="24" /></a>
<a href="https://github.com/guseoh?tab=repositories"><img src="https://img.shields.io/badge/Repositories-24292F?style=flat-square&amp;logo=github&amp;logoColor=white" alt="Repositories" height="24" /></a>

</div>

---

## About

백엔드의 **API·데이터 모델 설계**부터 트랜잭션과 데이터 정합성, 성능 측정과 운영 안정성까지 관심을 두고 있습니다. 구현 과정에서 선택한 설계와 검증 결과를 기록하며, **Codex와 테스트·CI를 활용한 개발 워크플로**도 함께 발전시키고 있습니다.

## Tech Stack

**Backend & Spring**

<p>
  <img src="https://img.shields.io/badge/Java-E76F00?style=flat-square&amp;logo=openjdk&amp;logoColor=white" alt="Java" height="26" />
  <img src="https://img.shields.io/badge/Spring_Boot-4B8F29?style=flat-square&amp;logo=springboot&amp;logoColor=white" alt="Spring Boot" height="26" />
  <img src="https://img.shields.io/badge/Spring_MVC-4B8F29?style=flat-square&amp;logo=spring&amp;logoColor=white" alt="Spring MVC" height="26" />
  <img src="https://img.shields.io/badge/Spring_Security-4B8F29?style=flat-square&amp;logo=springsecurity&amp;logoColor=white" alt="Spring Security" height="26" />
  <img src="https://img.shields.io/badge/Spring_Data_JPA-4B8F29?style=flat-square&amp;logo=spring&amp;logoColor=white" alt="Spring Data JPA" height="26" />
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&amp;logo=hibernate&amp;logoColor=white" alt="Hibernate" height="26" />
  <img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&amp;logo=gradle&amp;logoColor=white" alt="Gradle" height="26" />
  <img src="https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&amp;logo=junit5&amp;logoColor=white" alt="JUnit 5" height="26" />
</p>

**Database & Persistence**

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&amp;logo=mysql&amp;logoColor=white" alt="MySQL" height="26" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL" height="26" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&amp;logo=redis&amp;logoColor=white" alt="Redis" height="26" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&amp;logo=flyway&amp;logoColor=white" alt="Flyway" height="26" />
</p>

**Infrastructure & Observability**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker" height="26" />
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker Compose" height="26" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&amp;logo=nginx&amp;logoColor=white" alt="Nginx" height="26" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions" height="26" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&amp;logo=prometheus&amp;logoColor=white" alt="Prometheus" height="26" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&amp;logo=grafana&amp;logoColor=white" alt="Grafana" height="26" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&amp;logo=cloudflareworkers&amp;logoColor=white" alt="Cloudflare Workers" height="26" />
  <img src="https://img.shields.io/badge/Linux-333333?style=flat-square&amp;logo=linux&amp;logoColor=white" alt="Linux" height="26" />
</p>

**Web & Development Tools**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB" alt="React" height="26" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&amp;logo=nextdotjs&amp;logoColor=white" alt="Next.js" height="26" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" height="26" />
  <img src="https://img.shields.io/badge/Codex-24292F?style=flat-square&amp;logo=openai&amp;logoColor=white" alt="Codex" height="26" />
</p>
---

## Projects

### Featured Project

#### [PawCycle Commerce](https://github.com/guseoh/pawcycle-commerce)

<sub>Commerce · Subscription · Backend Reliability</sub>

반려동물 소모품의 일반 구매와 정기배송을 지원하는 커머스 프로젝트입니다. 상품 탐색부터 회원 인증, 정기배송 생성·변경·일정 관리, 주문·결제·배송 상태 모델까지 구현하며 백엔드 설계와 운영 안정성을 다루고 있습니다.

**주요 구현 및 검증** · 멱등성 기반 중복 요청 방지, 구독별 트랜잭션 실패 격리, SQL 조회 수 측정에 따른 N+1 개선

**기술** · Java · Spring Boot · Spring Security · JPA · MySQL · Flyway · Next.js · Docker

[Repository](https://github.com/guseoh/pawcycle-commerce) · [트랜잭션 격리 검증](https://github.com/guseoh/pawcycle-commerce/pull/106) · [멱등성 검증](https://github.com/guseoh/pawcycle-commerce/pull/108)

### Learning Projects

#### [CSForge](https://github.com/guseoh/csforge)

<sub>CS / Backend Learning Platform</sub>

Java·Spring·CS 지식을 영역·주제·개념·문항으로 구조화하고 학습 콘텐츠와 개인 학습 기록을 함께 관리하는 플랫폼입니다. 학습 화면뿐 아니라 콘텐츠 데이터가 변경되는 과정의 안전성도 학습·구현하고 있습니다.

**주요 구현 및 검증** · 기본 콘텐츠 준비 및 반복 실행 가능한 가져오기, Preview / Diff / Confirm 절차, 콘텐츠 키 기반 동기화와 기존 학습 데이터 보호

**기술** · Java · Spring Boot · PostgreSQL · Redis · React · TypeScript · Docker

[Repository](https://github.com/guseoh/csforge) · [Web](https://csforge-five.vercel.app/)

#### [Dark Todo Planner](https://github.com/guseoh/dark-todo-planner)

<sub>Personal Productivity Web App</sub>

오늘의 할 일과 월간·주간 캘린더, 프로젝트 관리, 메모·낙서장을 하나의 흐름으로 연결한 개인 작업 관리 웹 앱입니다. 화면 사용성과 데이터 관리, 배포·복구 과정을 함께 개선하고 있습니다.

**주요 구현 및 검증** · 프로젝트 Kanban·마일스톤, WYSIWYG 메모, 통합 검색, 브라우저 E2E 검증 및 암호화된 D1 백업

**기술** · React · TypeScript · Hono · Cloudflare Workers · D1 · GitHub Actions

[Repository](https://github.com/guseoh/dark-todo-planner) · [Web](https://dark-todo-planner.guseoh.workers.dev/)

---

## GitAnimals

<div align="center">

<a href="https://www.gitanimals.org/">
  <img src="https://render.gitanimals.org/farms/guseoh" width="600" alt="GitAnimals Farm" />
</a>

<p><a href="https://render.gitanimals.org/farms/guseoh">GitAnimals 농장 직접 보기</a></p>

</div>

---

## Latest Blog Posts

Java·Spring·JPA·HTTP·인프라 관련 학습과 검증 과정을 [기술 블로그](https://guseoh.github.io/)에 정리하고 있습니다.

<!-- BLOG-POST-LIST:START -->
<p><a href="https://guseoh.github.io/blog/jpa/persistence-context/">JPA 영속성 컨텍스트: 엔티티는 어떻게 관리될까?</a></p>
<p><a href="https://guseoh.github.io/blog/jpa/relationship-mapping/">JPA 연관관계 매핑: 객체 참조와 외래 키</a></p>
<p><a href="https://guseoh.github.io/blog/security/basic3/">Spring Security는 무엇을 해결할까?</a></p>
<!-- BLOG-POST-LIST:END -->

[전체 글 보기](https://guseoh.github.io/blog/)
