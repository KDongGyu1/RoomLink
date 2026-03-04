# 🏠 RoomLink (룸링크)
> **공동 생활 공간의 불공정함을 해결하고 관리를 자동화하는 모바일 애플리케이션**

최근 1인 가구의 증가와 함께 코리빙 하우스(Co-living) 시장이 급성장하고 있지만, 냉장고 공간 배분이나 청소 분담 등 사소한 생활 관리의 비효율성은 여전히 거주자 간 갈등의 주요 원인입니다. **RoomLink**는 이를 데이터와 자동화 시스템으로 해결합니다.

---



### 1. 지능형 Task 관리 및 자동화
- **Recurring Tasks**: 반복 주기를 설정하여 청소, 분리수거 등 정기적인 과업을 자동 생성합니다.

### 2. 데이터 기반의 공정성 시스템 (Fairness Engine)
- **Statistics**: 멤버별 Task 완료율과 기여도를 수치화하여 객관적인 데이터를 제공합니다.
- **Retrospects**: 수행된 과업에 대한 상호 피드백 시스템을 통해 단순 수행 여부를 넘어 퀄리티를 관리합니다.

### 3. 보안 및 권한 제어
- **RBAC (Role-Based Access Control)**: 그룹장과 일반 멤버의 권한을 분리하여 Task 상태 변경 및 그룹 설정을 안전하게 통제합니다.
- **JWT Auth**: NestJS의 Guard를 활용한 보안 인증으로 개인 및 그룹 데이터를 보호합니다.

---

## 🛠 Tech Stack

### Backend
- **Framework**: NestJS (Node.js)
- **Authentication**: Passport, JWT
- **Database**: PostgreSQL / TypeORM

### Frontend
- **Framework**: React Native (Cross-platform)
- **State Management**: Redux Toolkit / React Query (사용 중인 라이브러리로 수정)

---

## 🏗 System Architecture


1. **Client (React Native)**: 사용자 경험 중심의 UI/UX
2. **API Server (NestJS)**: 모듈형 아키텍처를 기반으로 한 확장성 있는 비즈니스 로직 처리.
3. **Task Engine**: 스케줄러를 통한 자동 과업 생성 및 통계 데이터 산출.

---

