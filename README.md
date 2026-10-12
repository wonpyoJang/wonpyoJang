## Hi there 👋

6년차 Flutter 크로스플랫폼 앱 개발자 장원표입니다. 「오늘학교」 · 「교촌치킨」처럼 일간 활성 사용자 5~10만 규모 서비스의 앱 파트를 맡아 왔습니다. 여러 개발자가 동시에 작업해도 유지보수하기 쉬운 구조를 원칙으로 삼고, 성장하는 서비스의 레거시를 이해하고 지키면서 구조 개선과 신규 개발을 함께 진행해 왔습니다.

*Flutter developer with 6 years of shipping and maintaining production apps (edu · commerce · healthcare). Comfortable collaborating in English through PRs and issues.*

- 누적 회원 150만 교육앱 「오늘학교」 모바일팀(4명) 리드 — 아키텍처 전환, CI/CD · 자동 배포 구축
- 가입자 200만 「교촌치킨」 등 멀티 브랜드 주문앱 — **Crash-free 사용자 88% → 98%**
- 의료기기 소프트웨어(SaMD) 시술자 앱 — 미국 · 프랑스어 버전 대응, 시연 · 납품
- Flame 게임엔진 + WebRTC 기반 RPG형 음성 채팅앱
- 국가슈퍼컴퓨팅경진대회 3회 수상 (최우수상 2회)

---

### 🔧 기술 스택

**Main**
- **App**: Flutter, Dart, BLoC, RxDart, Flame
- **Data**: Drift(Moor) · SQLite, Hive, Firebase(Firestore · Remote Config)
- **Architecture**: Clean Architecture, Injectable/get_it DI, 디자인 시스템
- **CI/CD**: GitHub Actions, Fastlane, flavor 기반 환경 분리, 점진적 배포
- **Monitoring · Analytics**: Crashlytics, Sentry, Datadog, GA4, Amplitude
- **Realtime**: WebRTC(Agora), FCM 사일런트 푸시

**Sub**
- **Frontend**: React, HTML/CSS
- **Backend**: FastAPI, Python, Firebase
- **DevOps**: Docker, AWS, Linux
- **Database**: PostgreSQL
- **Collaboration · AI**: Jira, Git Flow, Claude Code, Cursor, OpenAI API

---

### 💼 경력

**올쏘케어** — SaMD(근골격계 측정) 시술자용 앱 (2026.04 ~ 2026.10)
- Galaxy Tab 시술자 앱 풀스택 개발, 미국 · 프랑스어 버전 대응, 시연 · 납품 관리

**푸드대시** — 프랜차이즈 자사 배달 주문 앱 · 모바일 엔지니어 (2023.11 ~ 2025.12)
- 교촌치킨(누적 가입자 200만) · 읍천리382 · 자담치킨 등 멀티 브랜드 앱 신규 기능 개발과 운영 (BE 4 · App 2 · FE 2)
- 스탬프 프로모션, 상품권 · 쿠폰, 메뉴 시스템, 회원 관리, 주문 상태 알림 화면 개발, App Store · Play Store 관리
- 외부 플랫폼 상품권 등록 · 사용, 사일런트 푸시로 주문 접수 → 조리 → 배달 상태 실시간 반영, 회원가입 개편(KCB 본인인증)
- **Crash-free 사용자 비율 88% → 98%** (Firebase Crashlytics)
- 다중 BLoC · BlocListener 순환 이벤트 구조 개선, injectable DI 도입, 쿠폰 · 메뉴 옵션 시스템 객체지향 재설계, 디자인 시스템 적용률 50%

▸ 교촌치킨 주문 앱

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/kyochon-store.gif" width="240" alt="픽업 · 배달 선택 → 지도에서 매장 선택" /></td>
    <td align="center" width="33%"><img src="assets/kyochon-menu.gif" width="240" alt="메뉴 탐색 → 장바구니 담기" /></td>
    <td align="center" width="33%"><img src="assets/kyochon-checkout.gif" width="240" alt="쿠폰 적용 → 간편결제 수단 선택" /></td>
  </tr>
  <tr>
    <td align="center"><sub>픽업 · 배달 선택 → 지도에서 매장 선택</sub></td>
    <td align="center"><sub>메뉴 탐색 → 장바구니 담기</sub></td>
    <td align="center"><sub>쿠폰 적용 → 간편결제 수단 선택</sub></td>
  </tr>
</table>

▸ 읍천리382 주문 앱 (2024.10 ~ 2025.11)

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/eupcheonri-menu.gif" width="240" alt="메뉴 탐색 → 장바구니 담기" /></td>
    <td align="center" width="33%"><img src="assets/eupcheonri-options.gif" width="240" alt="세트 메뉴 옵션 선택" /></td>
    <td align="center" width="33%"><img src="assets/eupcheonri-checkout.gif" width="240" alt="배달 요청사항 → 결제" /></td>
  </tr>
  <tr>
    <td align="center"><sub>메뉴 탐색 → 장바구니 담기</sub></td>
    <td align="center"><sub>세트 메뉴 옵션 선택</sub></td>
    <td align="center"><sub>배달 요청사항 → 결제</sub></td>
  </tr>
</table>

**아테나스랩** — 오늘학교 앱 · 클라이언트 챕터 리드 (2021.08 ~ 2023.10)
- 누적 회원 150만 「오늘학교」: 시간표 · 급식표 · 학사 일정, 게시글 · 댓글 · GIF 이모티콘 커뮤니티 (Flutter, BLoC, RxDart, Injectable, Hive)
- 계층형 구조 + DI + RxDart 전역 이벤트 버스로 아키텍처 전환, 동적 게시판 생성 구조, 시간표 · 커뮤니티 멀티 프로필, 홈 요약
- 4명 모바일팀 리드: 2주 스프린트, OKR, 온보딩 문서, 코드 · 설계 · API 스펙 리뷰, 디자인 시스템 협업
- GitHub Actions + Fastlane CI/CD와 자동 출시, flavor 기반 환경 분리, Remote Config 피처 플래그 + Git Flow, 점진적 배포 도입
- Crashlytics · Sentry 품질 모니터링, GA · Amplitude 이벤트 체계 정립, release 모드 내장 로그 · API 호출 모니터링

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/onulschool-timetable.gif" width="240" alt="시간표에 과목 입력" /></td>
    <td align="center" width="33%"><img src="assets/onulschool-meal.gif" width="240" alt="급식표" /></td>
    <td align="center" width="33%"><img src="assets/onulschool-calendar.gif" width="240" alt="캘린더에 개인 일정 추가" /></td>
  </tr>
  <tr>
    <td align="center"><sub>시간표에 과목 입력</sub></td>
    <td align="center"><sub>급식표</sub></td>
    <td align="center"><sub>캘린더에 개인 일정 추가</sub></td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/onulschool-feed.gif" width="240" alt="커뮤니티 피드" /></td>
    <td align="center" width="33%"><img src="assets/onulschool-vote.gif" width="240" alt="투표 게시글" /></td>
    <td align="center" width="33%"><img src="assets/onulschool-comments.gif" width="240" alt="댓글 → 글쓰기" /></td>
  </tr>
  <tr>
    <td align="center"><sub>커뮤니티 피드</sub></td>
    <td align="center"><sub>투표 게시글</sub></td>
    <td align="center"><sub>댓글 → 글쓰기</sub></td>
  </tr>
</table>

**제트서브** — 모바일 엔지니어 (2020.05 ~ 2021.07)
- Flame 게임엔진 + WebRTC(Agora) 기반 RPG형 음성 채팅 앱: 캐릭터 상호작용 · 맵 이동, Pub/Sub 서버 기반 P2P 통신 설계
- 로컬(SQLite · Moor) ↔ 클라우드(Firestore) 채팅 데이터 모델 설계, 게시판 기능
- 회사가 수주한 외주 프로젝트로 동남아 웹툰 플랫폼 런칭

---

### 🛠 프로젝트

**스캔 촬영 앱 (개인 사이드 프로젝트)** — 스캔 기록 · 품질 추이, 칭호 · 배지, 캐릭터 키우기, 사다리 타기 미니게임, 의료진 1:1 채팅 (화면은 데모 데이터)

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/scan-badge.gif" width="240" alt="배지 획득 연출" /></td>
    <td align="center" width="33%"><img src="assets/scan-ladder.gif" width="240" alt="사다리 타기 애니메이션" /></td>
  </tr>
  <tr>
    <td align="center"><sub>배지 획득 연출</sub></td>
    <td align="center"><sub>사다리 타기 애니메이션</sub></td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/scan-chat-enter.gif" width="240" alt="대화방 입장 전 상대에게 보일 이름 선택" /></td>
    <td align="center" width="33%"><img src="assets/scan-chat-send.gif" width="240" alt="메시지 · 파일 대화와 전송" /></td>
    <td align="center" width="33%"><img src="assets/scan-chat-search.gif" width="240" alt="대화 목록 갱신 → 메시지 검색" /></td>
  </tr>
  <tr>
    <td align="center"><sub>대화방 입장 전 상대에게 보일 이름 선택</sub></td>
    <td align="center"><sub>메시지 · 파일 대화와 전송</sub></td>
    <td align="center"><sub>대화 목록 갱신 → 메시지 검색</sub></td>
  </tr>
</table>

**어드민 웹** — 3D 변환 파이프라인 · 운영 모니터링 · 사용성 피드백 · 회원 관리 (화면은 데모 데이터)

<table>
  <tr>
    <td align="center" width="50%"><img src="assets/admin-conversion-stats.gif" alt="3D 변환 통계 — 기간 전환 · 소요시간 · 성공률" /></td>
    <td align="center" width="50%"><img src="assets/admin-workers.gif" alt="변환 Worker 목록 → 상세 · 실시간 로그" /></td>
  </tr>
  <tr>
    <td align="center"><sub>3D 변환 통계 — 기간 전환 · 소요시간 · 성공률</sub></td>
    <td align="center"><sub>변환 Worker 목록 → 상세 · 실시간 로그</sub></td>
  </tr>
  <tr>
    <td align="center" width="50%"><img src="assets/admin-performance.gif" alt="라우트별 응답시간(p95) — 기간 전환" /></td>
    <td align="center" width="50%"><img src="assets/admin-feedback.png" alt="사용성 피드백 — NPS · CSAT 추이와 리포트 처리" /></td>
  </tr>
  <tr>
    <td align="center"><sub>라우트별 응답시간(p95) — 기간 전환</sub></td>
    <td align="center"><sub>사용성 피드백 — NPS · CSAT 추이와 리포트 처리</sub></td>
  </tr>
  <tr>
    <td align="center" width="50%"><img src="assets/admin-members.png" alt="회원 관리 — 가입 승인 · 역할 배정 · 접근 해제" /></td>
  </tr>
  <tr>
    <td align="center"><sub>회원 관리 — 가입 승인 · 역할 배정 · 접근 해제</sub></td>
  </tr>
</table>

**[AI 기반 감정 분석 일기 앱](https://github.com/wonpyoJang/diary_mobile_client)** — Flutter, Bloc, 생성형 AI 연동

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/diary-write.gif" width="240" alt="일기 작성" /></td>
    <td align="center" width="33%"><img src="assets/diary-emotion.gif" width="240" alt="AI가 일기에서 감정 추출" /></td>
    <td align="center" width="33%"><img src="assets/diary-card.gif" width="240" alt="감정 카드 생성 → 저장" /></td>
  </tr>
  <tr>
    <td align="center"><sub>일기 작성</sub></td>
    <td align="center"><sub>AI가 일기에서 감정 추출</sub></td>
    <td align="center"><sub>감정 카드 생성 → 저장</sub></td>
  </tr>
</table>

**[아날로그 타이머](https://github.com/wonpyoJang/analog-timer)** — 아날로그 시계 위에 세그먼트 타이머와 스톱워치를 함께 그리는 앱. Flutter(iOS · Android · macOS) + 웹

<table>
  <tr>
    <td align="center" width="25%"><img src="assets/timer-desktop.png" width="190" alt="데스크톱 — 타이머 링 · 스톱워치 · 세그먼트" /></td>
    <td align="center" width="25%"><img src="assets/timer-widget.png" width="190" alt="항상 위 위젯 모드" /></td>
    <td align="center" width="25%"><img src="assets/timer-overlay.png" width="190" alt="Android 오버레이 시계 · 타이머 pill" /></td>
    <td align="center" width="25%"><img src="assets/timer-multi.png" width="190" alt="멀티 타이머 동시 실행" /></td>
  </tr>
  <tr>
    <td align="center"><sub>데스크톱 — 타이머 링 · 스톱워치 · 세그먼트</sub></td>
    <td align="center"><sub>항상 위 위젯 모드</sub></td>
    <td align="center"><sub>Android 오버레이 시계 · 타이머 pill</sub></td>
    <td align="center"><sub>멀티 타이머 동시 실행</sub></td>
  </tr>
</table>

---

### 🎓 학력 · 수상

- **서울시립대학교** 전자전기컴퓨터공학 학사 (2014 ~ 2020) — 병렬소프트웨어 연구실 연구조교, 마이크로프로세서 강의조교
- **국가슈퍼컴퓨팅경진대회 3회 수상** (KISTI · UNIST) — 우수상 2016, 최우수상 2017 · 2018 · OpenMPI 멀티 프로세스 병렬 가속
- **핀테크 × 인슈어테크 해커톤 우수상** (KISA, 2019) — Hyperledger Fabric 기반 운전점수 산출 (Flutter · Node.js · GCP)
- **한국전자통신연구원(ETRI) 하계 인턴** (2019) — 차량용 보드 탑재 음성인식(Kaldi) 성능 분석
- 정보처리산업기사 · 육군 정보보호병 (2018 평창올림픽 정보보호 관제 지원)
- 영어 비즈니스 레벨 — 기술 문서 · 논문 독해, 스토어 리뷰어 소통

---

### 📫 연락처
- 이메일: jangwonpyo0@gmail.com
- 인스타그램: [@dev.logos](https://www.instagram.com/dev.logos?igsh=YWFoMjRnYWgyYTR6&utm_source=qr)
