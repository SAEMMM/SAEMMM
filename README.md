# 👩‍💻 Frontend Developer Shin Saem

> Type-safe UI · Reusable Architecture · Data Modeling

---

## 🧑‍💻 About Me

- React / Next.js 기반 프론트엔드 개발자 (3년)
- TypeScript 중심의 **타입 안정성 설계**
- 공용 컴포넌트 & 디자인 시스템 구축 경험
- 데이터 기반 UI (대시보드, 차트) 개발

---

## 🛠 Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript)

### State / Data
![React Query](https://img.shields.io/badge/ReactQuery-FF4154?style=flat&logo=reactquery)
![Apollo](https://img.shields.io/badge/Apollo-311C87?style=flat&logo=apollographql)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql)

### UI / Styling
![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat&logo=mui)
![styled-components](https://img.shields.io/badge/styled--components-DB7093?style=flat&logo=styledcomponents)

### Data Visualization
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs)

---

## 💡 What I Focus On

- 재사용 가능한 컴포넌트 설계
- 타입 안정성을 기반으로 한 UI 구조
- 데이터 가공 및 정규화를 통한 UI 추상화
- 렌더링 성능 최적화 (memo, dynamic import)

---

## 📌 Featured Projects

### 🔹 apoorpoor-refactor
> 기존 React 기반 가계부 프로젝트를 풀스택 모노레포로 재설계한 프로젝트

- Next.js 16 (App Router) + Hono.js + PostgreSQL/Prisma 기반 풀스택 구성
- pnpm workspace 모노레포 구조 (apps/web, apps/api, packages/db, packages/shared)
- JWT 인증, 가계부 CRUD, 월별 대시보드(캘린더·파이차트·막대차트) 구현
- MUI v7 + 토큰 기반 디자인 시스템 및 공용 UI 컴포넌트 구축
- 타입 계약을 shared 패키지로 분리하여 프론트·백엔드 간 타입 안정성 확보

👉 https://github.com/SAEMMM/apoorpoor-refactor

---

### 🔹 Chart Data Normalization
> 서로 다른 API 응답을 공통 차트 모델로 정규화하여 재사용 가능한 차트 구조 설계

- API별로 다른 응답 구조를 **공통 ChartModel로 정규화**
- Adapter 계층을 통해 데이터 가공 로직 분리
- 차트 컴포넌트가 데이터 구조에 의존하지 않도록 설계
- 하나의 차트 컴포넌트로 다양한 데이터 소스 재사용

👉 https://github.com/SAEMMM/chart-data-normalization

---

### 🔹 React Generic Select
> 타입 안전성을 보장하는 공용 Select 컴포넌트

- 제네릭 기반으로 value / options / onChange 타입 강제
- string / number / union 타입 지원
- 잘못된 사용을 컴파일 단계에서 차단

👉 https://github.com/SAEMMM/react-generic-select

---

### 🔹 Chart.js Overlap Chart
> 실행 데이터와 계획 데이터를 하나의 흐름으로 자연스럽게 표현하는 차트 구현

- 실제 값 + 예정 값을 하나의 라인으로 연결
- 데이터 가공을 통해 **중간 구간은 실선, 이후 구간은 점선 처리**
- 시간 축을 기준으로 데이터를 정렬 및 보정
- 단순 시각화가 아닌 **데이터 해석을 위한 차트 설계**

👉 https://github.com/SAEMMM/react-chartjs-overlap-demo.git

---

## 📝 Blog

👉 https://velog.io/@saemmmm

기술적인 고민과 해결 과정을 기록합니다.

---

## 📫 Contact

- saem030@naver.com

---

## 🔥 One Line

> 데이터를 구조화하고, 재사용 가능한 UI로 연결하는 프론트엔드 개발자입니다.
