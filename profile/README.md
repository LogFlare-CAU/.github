# 🚀 LOGFLARE
**A Mobile Log Notification App for Developers**

개발자들이 복잡한 서버 설정 없이 실시간으로 에러 로그를 관리하고 모바일로 즉각적인 알림을 받을 수 있도록 돕는 솔루션입니다

모바일 앱 다운르도는 [여기에서](https://github.com/LogFlare-CAU/android/releases) 가능합니다.

---

### 📦 Ecosystem & Repositories

LogFlare는 총 3계층의 오픈소스로 구성되어 있습니다:

* **📱 Android App** : 로그 확인 및 실시간 푸시 알림 수신을 위한 Kotlin 기반 앱  
  https://github.com/LogFlare-CAU/android
* **💻 Backend Server** : 로그 수집, 저장 및 FCM 알림 트리거를 담당하는 FastAPI 서버  
  https://github.com/LogFlare-CAU/Backend
* **🐍 Python Logger** : 기존 파이썬 프로젝트에 한 줄로 추가 가능한 커스텀 로거 라이브러리  
  https://github.com/LogFlare-CAU/Python-Logger

---

### 🛠 Tech Stack

#### Frontend
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) 
![Android Studio](https://img.shields.io/badge/android%20studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpack-compose&logoColor=white)

#### Backend
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

#### Infrastructure & Tools
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)

---

### 📌 Project Motivation
* **복잡한 서버 설정**: 개인 개발자나 소규모 팀에게는 로그 관리 서버 구축이 큰 진입 장벽입니다
* **웹 기반의 한계**: 기존 도구는 주로 웹 기반이라 모바일에서의 즉각적인 대응이 어렵습니다
* **접근성 문제**: 서버 설정 없이도 즉시 로그 알림을 확인할 수 있는 환경을 지향합니다

### ✨ Key Functions
* **실시간 로그 수집**: 개발 환경의 로그를 즉시 수집
* **스마트 알림**: 에러 발생 시 설정한 로그 레벨에 따라 푸시 알림 발송
* **필터링 & 관리**: 프로젝트별 무시 키워드 및 로그 레벨 상세 설정 가능

### 🏗 System Architecture

1. **Developer Local Environment**: 커스텀 로거를 통해 로그를 전송
2. **LogFlare Server**: 수신된 로그 저장 및 Firebase 알림 트리거
3. **Firebase (FCM)**: 안드로이드 앱으로 알림 전달
4. **Android App**: 로그를 수신하여 UI에 표시하고 분석 제공

---

### 👥 Team 7
| Name | Role | Responsibilities |
| :--- | :--- | :--- |
| **조진형 (Cho Jinhyoung)** | PM & Tech Lead | 프로젝트 총괄, 시스템 설계 및 풀스택 개발 |
| **정지현 (Jeong Jihyun)** | Frontend Developer | Kotlin 기반 UI 및 로직 개발, 데이터 바인딩 |
| **금지현 (Keum Jihyeon)** | Backend Developer | API 설계, 서버 개발, 실시간 알림 구현 |
| **박재윤 (Park Jaeyun)** | Planner / Designer | 서비스 플로우 설계, UI/UX 구조 기획 및 개발 지원 |
