# guseoh

**Java · Spring Backend Development**

문제의 원인을 재현하고, 설계 선택을 코드와 데이터로 검증하는 개발을 지향합니다.

Java와 Spring을 중심으로 백엔드 시스템을 만들고 있습니다. 기능 구현뿐 아니라 데이터 정합성, 트랜잭션, 성능, 운영 안정성을 함께 고민하고, 결정의 근거와 검증 결과를 기록합니다.

[Tech Blog](https://guseoh.github.io/) · [Repositories](https://github.com/guseoh?tab=repositories)

## Focus

- **Backend & Data** — 도메인 모델링, API 설계, 인증·인가, 트랜잭션과 데이터 정합성
- **Reliability & Operations** — 멱등성, 장애 격리, 성능 측정, 모니터링과 복구
- **Engineering Practice** — 테스트·CI 기반 검증, 설계 선택과 Trade-off 기록, Codex를 활용한 개발·리뷰

## Selected Projects

### [PawCycle Commerce](https://github.com/guseoh/pawcycle-commerce) — Commerce / Subscription

반려동물 소모품 구매와 정기배송을 구현하고, 실제 문제를 재현·측정하며 신뢰성을 개선하는 프로젝트입니다.

- 정기배송 생명주기, 주문·결제·배송 상태 모델과 회원별 권한 경계 구현
- 멱등성 기반 중복 요청 방지, 구독별 트랜잭션 장애 격리 및 정합성 검증
- SQL 조회 수를 측정한 뒤 N+1 문제를 개선하고, Prometheus·Grafana 기반 관측 자산 구성
- **기술:** Java, Spring Boot, Spring Security, JPA, MySQL, Flyway, Next.js, Docker

검증 기록: [구독 처리 실패 격리](https://github.com/guseoh/pawcycle-commerce/pull/106) · [멱등성 보존 및 정리](https://github.com/guseoh/pawcycle-commerce/pull/108)

> 현재 상시 운영 중인 프로덕션 배포는 없으며, 배포·장애 대응 기록은 저장소에 보존하고 있습니다.

### [CSForge](https://github.com/guseoh/csforge) — CS / Backend Learning Platform

Java·Spring·CS 개념을 구조화해 학습하고, 콘텐츠와 개인 학습 데이터를 함께 관리하는 플랫폼입니다.

- 학습 영역·주제·개념·문항을 구조화한 콘텐츠 모델과 학습 UI
- 콘텐츠 가져오기 전 Preview / Diff / Confirm 및 반복 실행 가능한 동기화 흐름
- 기존 학습 이력을 보호하는 데이터 처리와 테스트·자동 검증 작업
- **기술:** Java, Spring Boot, PostgreSQL, React, TypeScript, Docker

[Repository](https://github.com/guseoh/csforge) · [Web](https://csforge-five.vercel.app/)

### [Dark Todo Planner](https://github.com/guseoh/dark-todo-planner) — Personal Planning Web App

오늘의 할 일, 캘린더, 프로젝트, 메모를 연결한 개인 작업 관리 웹 애플리케이션입니다.

- 오늘·전체 Todo·월간/주간 캘린더·프로젝트·메모 기능 구현
- Cloudflare Workers / D1 기반 API·데이터 관리와 백업·복원 절차 구성
- 타입 검사, 테스트, 브라우저 E2E 및 배포 후 헬스 체크를 CI에 연결
- **기술:** React, TypeScript, Hono, Cloudflare Workers, D1, GitHub Actions

[Repository](https://github.com/guseoh/dark-todo-planner) · [Web](https://dark-todo-planner.guseoh.workers.dev/)

## Learning & Writing

- **[Mini Tomcat](https://github.com/guseoh/mini-tomcat)** — Java 표준 라이브러리로 HTTP 서버·서블릿 컨테이너 내부 동작을 단계적으로 학습하는 프로젝트 (현재 기반 단계)
- **[Tech Blog](https://guseoh.github.io/)** — Java, Spring, JPA, HTTP, 네트워크와 인프라를 이해하고 검증한 내용을 정리하는 기록 공간

## Technologies

| Area | Technologies |
| --- | --- |
| Backend | Java · Spring Boot · Spring Security · JPA / Hibernate |
| Data | MySQL · PostgreSQL · Flyway |
| Infrastructure & Quality | Docker · Nginx · GitHub Actions · Prometheus · Grafana · JUnit |
| Frontend & Web | React · Next.js · TypeScript · Astro |

## Recent Writing

<!-- BLOG-POST-LIST:START -->
- [JPA 영속성 컨텍스트: 엔티티는 어떻게 관리될까?](https://guseoh.github.io/blog/jpa/persistence-context/)
- [JPA 연관관계 매핑: 객체 참조와 외래 키](https://guseoh.github.io/blog/jpa/relationship-mapping/)
- [Spring Security는 무엇을 해결할까?](https://guseoh.github.io/blog/security/basic3/)
<!-- BLOG-POST-LIST:END -->

[More posts](https://guseoh.github.io/blog/)
