## ⛳ 골방(Golbang) – 골프 모임 관리 플랫폼
PPT 링크: [PPT](https://docs.google.com/presentation/d/1QBwRqSsVbyO0bk7C9iwoeRpyBRHcH1IeGY_BCQe1XKA/edit?usp=sharing)

### 📌 개요
- **의미:** 골프(Golf) + 방(Bang)  
- **목표:** 골프 모임 생성, 일정 공유, 게임 기록까지 한 번에 관리할 수 있는 플랫폼 제공
- **대상:** 골프 동호회, 골프 모임 사용자
- **진행 기간:** 2024.02 ~ 현재
- **출시:**  
  - [Google Play](https://play.google.com/store/apps/details?id=com.ines.golbang&hl=ko)  
  - [App Store](https://apps.apple.com/kr/app/golbang/id6740680010)  

---

### 🎯 문제 정의
1. 골프 모임 일정·스코어 관리가 분산되어 비효율적  
2. 스코어 기록을 개별적으로 관리해야 함(구글 시트 등)  
3. 모임 구성원 간 기록·일정 공유의 불편함

---

### 💡 솔루션
- 모임 중심의 일정·스코어 통합 관리  
- 실시간 스코어 기록 공유(WebSocket)  
- 경기 후 통계·랭킹 자동 집계  
- 유저 친화적인 UI/UX와 브랜드 아이덴티티 적용

---

### 🛠 주요 기능
- **모임 관리:** 모임 생성/참여, 일정 생성/조회
- **게임 관리:** 홀별 점수 입력, 스코어 집계, 랭킹 조회
- **통계 기능:** 전체 랭킹, 개인별 통계
- **알림 기능:** 일정 및 이벤트 푸시 알림(FCM)
- **멀티 플랫폼:** Android / iOS 동시 지원

---

### 🖥 기술 스택
**Frontend:** Flutter, Dart   
**Backend:** DjangoRestFramework, Python, Celery   
**Collaboration:** GitHub, Discord, Notion, Figma

---