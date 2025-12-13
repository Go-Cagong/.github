# ☕ Go-Cagong (고카공)

**카공하기 좋은 카페를 가장 빠르고 정확하게 찾는 방법**

Go-Cagong은 일반 카페 중에서 *카공(카페에서 공부/작업)*에 적합한 장소를 손쉽게 찾을 수 있도록 만드는 서비스입니다.
지도 기반 탐색, AI 요약 리뷰, 영수증 인증 리뷰 기능을 통해 **신뢰도 높은 카페 정보 플랫폼**을 제공합니다.

발표자료 : https://www.canva.com/design/DAG6nwMSaPg/WMz9Aa9lbIDJp9E2GykRiQ/view?utm_content=DAG6nwMSaPg&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hc2301de2a6

---

## 🚀 핵심 기능

### **1) 소셜 로그인 기반 회원 기능**

번거로운 회원가입 없이 바로 시작할 수 있어요.

* 카카오 로그인
* 구글 로그인
* 네이버 로그인

OAuth 기반 인증으로 간편하고 안전하게 이용할 수 있습니다.

---

### **2) 메인 화면 – 지도 기반 카페 탐색**

앱을 실행하면 가장 먼저 **지도 화면**이 나타나며, 주변 카페를 토글 형태로 확인할 수 있습니다.

* 내 주변 카페 자동 표시
* 상단 필터 기능 제공

  * 분위기
  * 아메리카노 가격
  * 주차 가능 여부

사용자는 원하는 조건에 맞춰 **카공하기 좋은 카페만 골라서 탐색**할 수 있습니다.

---

### **3) 카페 상세 정보 + AI 요약 리뷰**

카페 상세 화면에서는 다음 정보를 제공합니다.

* 카페 사진
* 운영시간
* 분위기/공간 정보
* 전체 사용자 리뷰
* **AI 리뷰 요약 제공 (네이버 리뷰 크롤링 기반)**

사용자 리뷰가 너무 많아 일일이 읽기 힘들어도,
AI가 자동으로 요약해 핵심만 보여주기 때문에 **빠른 판단이 가능**합니다.

---

### **4) 저장 기능 (즐겨찾기 대체 기능)**

사용자는 관심 있는 카페를 저장해둘 수 있습니다.
마이페이지에서 “저장한 카페” 목록을 한 번에 확인할 수 있어요.

---

### **5) 영수증 인증 기반 리뷰 기능**

리뷰의 신뢰도를 높이기 위해 **영수증 인증 리뷰 시스템**을 도입했습니다.

* 사용자가 카페 영수증을 촬영
* Google ML Kit OCR로 영수증 분석
* 실제 방문 여부를 검증한 뒤 리뷰 작성 가능

허위 리뷰를 차단함으로써, **더 정직한 리뷰 생태계**를 구축합니다.

---

## 🧠 AI 기능

### **AI 리뷰 요약**

네이버 카페 리뷰를 크롤링하여
→ 사용자 경험 중심 문장을 추출
→ 자연어 처리 기반 자동 요약을 제공

“이 카페가 어떤 느낌인지” 몇 줄로 바로 파악할 수 있습니다.

---

## 🛠 Tech Stack & System Architecture

### **Backend**

* **Spring Boot (Java 17)**
* **JWT Authentication**
* **MariaDB**
* **AWS EC2 (배포 환경)**
* **AWS S3 (이미지 저장)**

### **Frontend**

* **Android Studio (Java)**
* **네이버 지도 API**
* **Google ML Kit OCR (영수증 인식)**

### **AI / Data**

* **네이버 리뷰 자동 크롤링 및 텍스트 요약 모델**

<!-- <img width="2816" height="1536" alt="go_cagong_sys-arch" src="https://github.com/user-attachments/assets/b47533df-db0a-485f-bb18-4a406b42e856" /> -->
<img width="949" height="411" alt="고카공_시스템아키텍쳐" src="https://github.com/user-attachments/assets/a2cb9999-a0b0-4978-a450-2c7bea0524d4" />


## 🙎‍♂️ Our Team
| 김재웅 | 이재혁 | 송창식 | 안재일 | 박혜일 |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://github.com/grbuguj.png" width="150px" height="150px"/> | <img src="https://github.com/jaehyuk917.png" width="150px" height="150px" /> | <img src="https://github.com/TedCkd.png" width="150px" height="150px" /> | <img src="https://github.com/jaeiling.png" width="150px" height="150px"> | <img src="https://github.com/Tsunami1030.png" width="150px" height="150px"/> |
| [@grbuguj](https://github.com/grbuguj) | [@jaehyuk917](https://github.com/jaehyuk917) | [@TedCkd](https://github.com/TedCkd) | [@jaeiling](https://github.com/jaeiling) | [@Tsunami1030](https://github.com/Tsunami1030) |
| 팀장 | 팀원 | 팀원 | 팀원 | 팀원 |
| FullStack | FrontEnd | FrontEnd | BackEnd | BackEnd |

*copyright 2025. [Team Go-Cagong] All Rights Reserved.*

