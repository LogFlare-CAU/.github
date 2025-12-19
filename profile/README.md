# 🚀 LOGFLARE
**A Mobile Log Notification App for Developers**

개발자들이 서버 설정의 번거로움 없이 실시간으로 에러 로그를 관리하고 알림을 받을 수 있도록 돕는 모바일 솔루션입니다.

---

### 📌 Project Motivation
기존 로그 관리 도구들의 한계를 극복하고자 시작되었습니다:
* **복잡한 설정**: 개인 개발자나 소규모 팀이 서버를 직접 구축하기에는 진입 장벽이 높습니다. 
* **웹 중심 환경**: 대부분의 도구가 웹 기반이라 이동 중 즉각적인 대응이 어렵습니다. 
*    **접근성 제한**: 언제 어디서나 에러 응답을 즉시 할 수 있는 모바일 환경이 필요합니다.

### ✨ Key Functions
*   **실시간 로그 수집**: 개발 환경에서 발생하는 로그를 즉시 수집합니다. 
*    **푸시 알림**: 중요한 에러 발생 시 모바일 푸시 알림을 발송합니다. 
*    **로그 레벨 필터링**: DEBUG, INFO, WARNING, ERROR 등 단계별 필터링을 지원합니다. 
*    **프로젝트 기반 관리**: 여러 개의 프로젝트 로그를 독립적으로 관리할 수 있습니다.

### 🏗 System Architecture


1.    **Developer Local Environment**: 커스텀 로거를 통해 로그를 전송합니다. 
2.    **LogFlare Server (Flask + Socket.IO)**: 로그를 저장하고 푸시 알림을 트리거합니다. 
3.    **Firebase (FCM)**: 안드로이드 앱으로 알림을 전달합니다. 
4.    **Android App**: 로그를 수신하여 UI에 표시하고 분석 환경을 제공합니다.

### 🛠 Tech Stack
*    **Frontend**: Kotlin (Android Studio) 
*    **Backend**: Python (FastAPI, SQLAlchemy), SQLite 
*    **Infrastructure**: Firebase Cloud Messaging (FCM) 
*    **Collaboration**: Figma, Notion, GitHub

###  | 👥 Team 7 (Application Development for Mobile Computer 02) 
| Name | Role | Primary Responsibilities |
| :--- | :--- | :--- |
  | **조진형 (Cho Jinhyoung)** | PM & Tech Lead  | 프로젝트 총괄, 시스템 설계 및 풀스택 개발  |
  | **정지현 (Jeong Jihyun)**   | Frontend Developer   | Kotlin 기반 UI 및 로직 개발, 데이터 바인딩  |
  | **금지현 (Keum Jihyeon)**    | Backend Developer | API 설계, 서버 개발, 실시간 알림 구현 |
  | **박재윤 (Park Jaeyun)**   | Planner / Designer  | 서비스 플로우 설계, UI/UX 구조 기획 및 개발 지원 |

