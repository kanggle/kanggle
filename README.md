# 👋 kanggle

**백엔드 엔지니어 — 플랫폼 설계 · 테스트 디시플린 · 도메인 모델링 중심**

Spring Boot · Java 21 · 이벤트 기반 마이크로서비스 · Hexagonal Architecture · Testcontainers

---

## 🎯 Featured Projects

### [wms-platform](https://github.com/kanggle/wms-platform) · Warehouse Management System

창고관리시스템 백엔드 플랫폼. 마스터 데이터 서비스 + API 게이트웨이로 구성된 production-grade 백엔드 레퍼런스.

- **Stack**: Java 21 · Spring Boot 3.4 · Postgres 16 · Kafka (KRaft) · Redis · Docker
- **Aggregates**: Warehouse · Zone · Location · SKU · Lot (5/6 — Partner deferred)
- **Architecture**: Hexagonal (Ports & Adapters) · Outbox pattern · Idempotency filter · JWT + Redis rate-limit(fail-open)
- **Testing**: @WebMvcTest slices · H2 fast tests · Testcontainers Postgres/Kafka/Redis · JSON Schema contract harness · gateway↔master live-pair e2e
- **Ops**: Actuator metrics · Outbox publisher backpressure · 일일 Lot expiration 스케줄러
- 📂 개발 과정 전체 히스토리 보려면: **[monorepo-lab](https://github.com/kanggle/monorepo-lab)**

### [ecommerce-microservices-platform](https://github.com/kanggle/ecommerce-microservices-platform)

도메인 기반 마이크로서비스 이커머스 플랫폼 — Spring Boot · Next.js · Kafka · Kubernetes

### [global-account-platform](https://github.com/kanggle/global-account-platform)

글로벌 계정·인증·보안 플랫폼 — Spring Boot microservices

---

## 🧪 Development Workspace

**[monorepo-lab](https://github.com/kanggle/monorepo-lab)** — 실제 개발 환경이자 shared library의 집. Task-driven workflow(`ready → in-progress → review → done`), spec-first 설계, 리뷰 디시플린이 여기서 일어납니다. 개별 프로젝트 레포는 여기서 추출된 스냅샷.

모노레포를 보면 알 수 있는 것:
- 커밋 메시지 · PR 흐름으로 읽는 **엔지니어링 프로세스**
- `platform/` · `rules/` · `libs/` · `.claude/`로 분리된 **재사용 가능한 기반**
- 태스크 라이프사이클과 리뷰 결과로 추적되는 **의사 결정 기록**

---

## 📫 Contact

- Email: **kkangchang99@gmail.com**
