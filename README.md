> 📌 **본 저장소는 [KB IT's Your Life 6기 스켈레톤 팀 프로젝트](https://github.com/seunguk99/KB17th_Team_6)를 Fork하여,  
> 개인 포트폴리오 용도로 정리한 저장소입니다.**  
> 아래는 본 프로젝트에서의 제 기여 내용입니다.

## 👤 나의 기여 요약

- `/stores/userStore.js`, `/pages/UserSelection.vue`, `/pages/ProfilePage.vue` 등 **유저 관련 기능 구현**
- `/components/layout/` 내 `Header.vue`, `Footer.vue`, `DefaultLayout.vue` 등 **전체 레이아웃 컴포넌트 제작**
- `/components/nav/` 내 `NavBar.vue`, `MenuGroup.vue`, `MenuItem.vue` 등 **네비게이션 바 설계 및 메뉴 동적 렌더링 구현**
- Composition API, Vue Router를 활용한 **SPA 구조 설계**
- Composition API 및 Slot을 활용한 **재사용 가능한 기본 레이아웃 구조 설계**
- **Vue Router + Composition API 기반 페이지 라우팅 설계**
- 반응형 UI 구성 및 Bootstrap 기반 레이아웃 정렬 적용
- 팀 협업 구조 설계 및 Git flow 관리 일부 참여

## 🗂️ 프로젝트 문서 및 자료

- 📄 [Notion 기획 & 과정 문서](https://peppermint-heaven-8c4.notion.site/6-1ced22ad250b802691eac664031e00ee)
  - 프로젝트 설계, 역할 분담
  - Figma 기반 페이지 UI 설계
  - 테스트 및 피드백
  - 최종 발표용 PPT 포함

> 👉 Notion을 통해 팀 전체 협업 과정을 기록하였으며,  
> Figma를 활용한 설계와 PPT 발표 자료도 포함되어 있습니다.

---

# 💰 가계부 프로젝트

KB IT's Your Life 6기 프론트엔드 스켈레톤 프로젝트로 진행하였습니다.

Vue.js 기반의 SPA 가계부 애플리케이션입니다. 사용자 선택, 거래 내역 관리, 필터링 및 프로필 수정 기능 등을 포함하며, 팀 협업 구조로 개발되었습니다.

---

## 📌 주요 기능

- 사용자 선택 및 로그인 상태 유지 (Pinia + sessionStorage)
- 월/주/일/카테고리별 거래 내역 필터링
- 수입/지출 및 순이익 요약
- 거래 등록, 상세 보기, 수정 기능
- 사용자 프로필 조회 및 정보 수정
- JSON Server를 통한 로컬 API 서버 구축

---

## 🛠️ 사용 기술 스택

| 구분          | 기술                    |
| ------------- | ----------------------- |
| 프레임워크    | Vue 3 (Composition API) |
| 상태 관리     | Pinia                   |
| 라우팅        | Vue Router              |
| UI 프레임워크 | Bootstrap 5             |
| 아이콘        | Font Awesome            |
| API 통신      | Axios                   |
| 목서버        | JSON Server             |
| 차트 시각화   | Chat.js                 |
| 캘린더        | Vue-Cal                 |
| 협업 도구     | Git / GitHub            |

---

## 📁 프로젝트 구조

```
src/
├── assets/
│   └── main.css
├── Chart/
│   └── chart.js
├── components/
│   ├── layout/
│   │   ├── DefaultLayout.vue
│   │   ├── Header.vue
│   │   └── Footer.vue
│   ├── nav/
│   │   ├── NavBar.vue
│   │   ├── MenuGroup.vue
│   │   └── MenuItem.vue
│   └── transaction/
│       ├── QuickAdd.vue
│       ├── SelectedDayList.vue
│       ├── TransactionList.vue
│       ├── TransactionGroup.vue
│       └── TransactionItem.vue
├── pages/
│   ├── UserSelection.vue
│   ├── HomePage.vue
│   ├── TransactionHistory.vue
│   ├── TransactionWritePage.vue
│   ├── TransactionEditPage.vue
│   ├── DetailTransactionPage.vue
│   ├── ProfilePage.vue
│   └── EditProfilePage.vue
├── router/
│   └── index.js
├── stores/
│   ├── userStore.js
│   └── transactionStore.js
└── App.vue
└── main.js
```

## ⚙️ 설치 및 실행

```bash
# 1. 패키지 설치
npm install

# 2. JSON Server 설치
npm install -g json-server@0.17.3

# 3. JSON Server 실행
json-server db.json

# 4. Vite 개발 서버 실행
npm run dev
```

## 👥 팀원

| 이름   | GitHub                                           |
| ------ | ------------------------------------------------ |
| 김승욱 | [@seunguk99](https://github.com/seunguk99)       |
| 박주용 | [@ju1645](https://github.com/ju1645)             |
| 양민영 | [@Minyoung06](https://github.com/Minyoung06)     |
| 윤예림 | [@StarWhale0w0](https://github.com/StarWhale0w0) |
| 이유미 | [@ll-04](https://github.com/ll-04)               |
