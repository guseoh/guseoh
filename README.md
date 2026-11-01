<div align="center">

# guseoh

**Java · Spring Backend Developer**

Java와 Spring으로 백엔드 시스템을 만들고, 설계한 내용을 코드와 데이터로 검증합니다.  
배운 것은 프로젝트와 글로 남기고 있습니다.

<a href="https://guseoh.github.io/"><img src="https://img.shields.io/badge/Tech_Blog-24292F?style=flat-square&amp;logo=github&amp;logoColor=white" alt="Tech Blog" height="24" /></a>
<a href="https://github.com/guseoh?tab=repositories"><img src="https://img.shields.io/badge/Repositories-24292F?style=flat-square&amp;logo=github&amp;logoColor=white" alt="Repositories" height="24" /></a>

</div>

---

## About

요구사항을 도메인과 API로 풀어내는 설계 과정에 관심이 있습니다. 기능 구현 이후에는 트랜잭션, 데이터 정합성, 성능, 장애 상황을 재현하고 확인하는 것을 중요하게 생각합니다.

> **Current Focus** · Software Design / AI-assisted Development / Reliability

---

## Projects


<details>
<summary><strong>PawCycle Commerce</strong> — 반려동물 소모품 구매와 정기배송</summary>

<br>

정기배송의 전체 흐름을 구현하면서 데이터 정합성과 운영 안정성을 검증하는 커머스 프로젝트입니다. 상품 구매·구독 변경·배송 일정 관리부터 멱등성, 구독별 트랜잭션 실패 격리, N+1 측정 및 개선까지 다루고 있습니다.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/architecture/pawcycle-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/architecture/pawcycle-light.svg" />
    <img src="./assets/architecture/pawcycle-light.svg" width="760" alt="PawCycle Commerce — 주요 구성 요소와 데이터 흐름을 요약한 아키텍처" />
  </picture>
</p>

[Repository](https://github.com/guseoh/pawcycle-commerce) · [설계·검증 기록](https://github.com/guseoh/pawcycle-commerce#readme)

</details>


<details>
<summary><strong>CSForge</strong> — CS 개념 및 학습 이력 관리 플랫폼</summary>

<br>

Java·Spring·CS 개념을 영역과 주제별로 구조화하고 학습 기록과 연결한 플랫폼입니다. 콘텐츠를 반복해서 가져오거나 동기화할 때 기존 학습 데이터를 보호하는 흐름도 구현했습니다.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/architecture/csforge-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/architecture/csforge-light.svg" />
    <img src="./assets/architecture/csforge-light.svg" width="760" alt="CSForge — 주요 구성 요소와 데이터 흐름을 요약한 아키텍처" />
  </picture>
</p>

[Repository](https://github.com/guseoh/csforge) · [Live Demo](https://csforge-five.vercel.app/)

</details>

<details>
<summary><strong>Dark Todo Planner</strong> — 일정·프로젝트·메모 통합 플래너</summary>

<br>

할 일·월간/주간 캘린더·프로젝트 Kanban·메모를 연결한 개인 작업 관리 웹 앱입니다. 사용 경험을 개선하면서 E2E 테스트, Cloudflare D1 백업 및 배포 자동화를 구성했습니다.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/architecture/dark-todo-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/architecture/dark-todo-light.svg" />
    <img src="./assets/architecture/dark-todo-light.svg" width="760" alt="Dark Todo Planner — 주요 구성 요소와 데이터 흐름을 요약한 아키텍처" />
  </picture>
</p>

[Repository](https://github.com/guseoh/dark-todo-planner) · [Live Demo](https://dark-todo-planner.guseoh.workers.dev/)

</details>

---

## Tech Stack

**Backend & Spring**

<p>
  <img src="https://img.shields.io/badge/Java-E76F00?style=flat-square&amp;logo=openjdk&amp;logoColor=white" alt="Java" height="25" />
  <img src="https://img.shields.io/badge/Spring_Boot-4B8F29?style=flat-square&amp;logo=springboot&amp;logoColor=white" alt="Spring Boot" height="25" />
  <img src="https://img.shields.io/badge/Spring_MVC-4B8F29?style=flat-square&amp;logo=spring&amp;logoColor=white" alt="Spring MVC" height="25" />
  <img src="https://img.shields.io/badge/Spring_Security-4B8F29?style=flat-square&amp;logo=springsecurity&amp;logoColor=white" alt="Spring Security" height="25" />
  <img src="https://img.shields.io/badge/Spring_Data_JPA-4B8F29?style=flat-square&amp;logo=spring&amp;logoColor=white" alt="Spring Data JPA" height="25" />
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&amp;logo=hibernate&amp;logoColor=white" alt="Hibernate" height="25" />
  <img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&amp;logo=gradle&amp;logoColor=white" alt="Gradle" height="25" />
  <img src="https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&amp;logo=junit5&amp;logoColor=white" alt="JUnit 5" height="25" />
</p>

**Database & Persistence**

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&amp;logo=mysql&amp;logoColor=white" alt="MySQL" height="25" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL" height="25" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&amp;logo=redis&amp;logoColor=white" alt="Redis" height="25" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&amp;logo=flyway&amp;logoColor=white" alt="Flyway" height="25" />
</p>

**Infrastructure & Observability**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker" height="25" />
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker Compose" height="25" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&amp;logo=nginx&amp;logoColor=white" alt="Nginx" height="25" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions" height="25" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&amp;logo=prometheus&amp;logoColor=white" alt="Prometheus" height="25" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&amp;logo=grafana&amp;logoColor=white" alt="Grafana" height="25" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&amp;logo=cloudflareworkers&amp;logoColor=white" alt="Cloudflare Workers" height="25" />
  <img src="https://img.shields.io/badge/Linux-333333?style=flat-square&amp;logo=linux&amp;logoColor=white" alt="Linux" height="25" />
</p>

**Web & Development Tools**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB" alt="React" height="25" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&amp;logo=nextdotjs&amp;logoColor=white" alt="Next.js" height="25" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" height="25" />
  <img src="https://img.shields.io/badge/Codex-24292F?style=flat-square&amp;logo=openai&amp;logoColor=white" alt="Codex" height="25" />
</p>

---

## Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
<p><sub>01</sub> &emsp; <a href="https://guseoh.github.io/blog/jpa/persistence-context/">JPA 영속성 컨텍스트: 엔티티는 어떻게 관리될까?</a></p>
<p><sub>02</sub> &emsp; <a href="https://guseoh.github.io/blog/jpa/relationship-mapping/">JPA 연관관계 매핑: 객체 참조와 외래 키</a></p>
<p><sub>03</sub> &emsp; <a href="https://guseoh.github.io/blog/security/basic3/">Spring Security는 무엇을 해결할까?</a></p>
<!-- BLOG-POST-LIST:END -->

<p align="right"><a href="https://guseoh.github.io/blog/">모든 글 보기</a></p>

---

## GitAnimals

<div align="center">

<a href="https://www.gitanimals.org/">
  <img src="https://render.gitanimals.org/farms/guseoh" width="720" alt="GitAnimals Farm" />
</a>

</div>
