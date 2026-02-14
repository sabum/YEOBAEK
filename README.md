# YEOBAEK — 여백

> 채우지 않음의 미학. 가장 한국적인 것이 가장 세계적인 것.

---

## 🔗 Live Demo

| Version | Link | Description |
|---------|------|-------------|
| **V1** | [sabum.github.io/YEOBAEK](https://sabum.github.io/YEOBAEK/) | Vertical Scroll |
| **V2** | [sabum.github.io/YEOBAEK/v2](https://sabum.github.io/YEOBAEK/v2/) | Horizontal Scroll |

---

## 소개

DEEPONDÉ의 프리미엄 니치 향수 브랜드 **여백(YEOBAEK)** 웹사이트.
조선 백자 달항아리의 철학을 향수로 구현한 브랜드 스토리텔링 사이트입니다.

---

## V2 — Horizontal Scroll Experience

V2는 기존 세로 스크롤 사이트를 **가로 스크롤 기반의 몰입형 경험**으로 재구성한 버전입니다.

### ✨ 주요 기능

- **가로 스크롤 네비게이션** — 마우스 휠, 키보드 화살표, 트랙패드로 자연스러운 수평 이동
- **Ping-Pong 배경 영상** — Hero & Craft 섹션에 정방향→역방향 자동 반복 재생 백그라운드 비디오
- **6개 섹션 구성** — Hero → Philosophy → Collection → Craft → Space → Contact
- **센터 정렬 내비게이션** — 로고 + 메뉴 중앙 배치
- **Progress Bar** — 상단 진행률 표시로 현재 스크롤 위치 시각화
- **섹션 인디케이터** — 현재 섹션 번호를 실시간으로 표시
- **Reveal 애니메이션** — 각 섹션 진입 시 요소가 순차적으로 등장
- **반응형 디자인** — 모바일에서는 자동으로 세로 스크롤 모드 전환

### 🎬 배경 영상 처리

영상의 자연스러운 무한 루프를 위해 **ping-pong 기법**을 적용:
1. 원본 영상에 역방향 영상을 결합
2. `<video loop autoplay>` 으로 무한 반복
3. 정방향 → 역방향 → 정방향… 끊김 없는 재생

---

## 시그니처 라인 — The Timeline

| # | 이름 | 한국어 | 키노트 |
|---|------|--------|--------|
| 01 | Moon Soil | 빚어내는 흙 | Steamed Rice · White Clay |
| 02 | Kiln Breath | 가마의 숨 | Pink Pepper · Ink · Birch Tar |
| 03 | Void Air | 비움의 공기 | Morning Dew · Magnolia |

---

## 기술 스택

- **Core** — HTML / CSS / Vanilla JS
- **Typography** — Cormorant Garamond · Noto Serif KR
- **Video** — moviepy (Python) 를 활용한 ping-pong 영상 생성
- **Design** — 에디토리얼 레이아웃 · CSS 애니메이션 · Glassmorphism
