## 📊 기획배경(공공데이터 분석)
  20대 후반의 실업률이 증가하고, 졸업자의 유지취업률이 하락하는 등 청년층을 중심으로 취업난이 심화되고 있습니다. 
  실제 통계 데이터를 바탕으로 청년층 취업률이 얼마나 감소하였는지 검증하고자 시각화 분석을 진행해보았습니다.
<img width="591" height="329" alt="employ_rate" src="https://github.com/user-attachments/assets/ddb4e3d5-bcd4-4002-bbd8-ea31dd1eee66" />

### 20~30대의 취업률
<img width="480" height="325" alt="data-analysis" src="https://github.com/user-attachments/assets/e91e0cd1-85ff-42ac-b304-841148160667" />

시각화된 자료를 통해 연도별 20~30대 취업률 수를 비교한 결과 30대는 어느정도 상승세를 보이는 반면, 20대는 다시 하락세를 보이는 것을 확인했습니다.

[📄 기획배경 시각화](https://github.com/hjjung990927/study-Data-Analysis/blob/master/data-analysis/kok/kok_data_analysis.ipynb) 

#### 주요 감소 요인
- **기업의 경력직 선호 및 수시 채용 확대**: 신입보다는 경력이 있는 직원을 선호하고, 공채 대신 수시로 인력을 채용하는 경향이 강해지면서 청년층의 신규 진입이 더욱 어려워졌습니다.
- **경기 침체 및 경제 불확실성**: 대내외 경제 불확실성과 수익성 악화로 인해 기업들이 경영 긴축에 나서면서 신규 채용을 줄이고 있습니다.
- **양질의 일자리 부족**: 청년층이 선호하는 대기업이나 공공기관의 신규 채용이 감소하고 있으며, 구직자들의 기대 임금 수준과 실제 일자리 간의 격차가 존재합니다.

### 결과
  20대 청년층의 취업률은 최근 몇 년간 지속적으로 감소하는 경향을 보였습니다. <br>
  반면 30대의 취업률은 소폭 상승하여 세대 간 취업 양극화가 나타나는 것으로 확인되었습니다. <br>
  주요 요인으로는 기업의 경력직 선호와 수시 채용 확대, 경기 침체로 인한 신규 채용 감소, 청년층이 선호하는 양질의 일자리 부족 등이 복합적으로 작용한 것으로 분석됩니다. <br>
  이러한 결과는 청년층을 대상으로 한 취업 지원 정책 강화, 신입 구직자에 대한 채용 확대, 청년 맞춤형 직무 교육 제공 등 실질적 대책이 필요함을 나타냅니다.
  
### 출처
  [🌐 KOSIS 국가통계포털](https://kosis.kr/)

## 🎨 UI/UX 설계 및 클론코딩

### 벤치마킹 대상: 로켓펀치

-  **화면 구현 능력단위**에서 배운 HTML, CSS, JavaScript를 활용하여
벤치마킹한 ‘로켓펀치’ 화면을 클론코딩했습니다.
-  CSS Flex와 Grid를 이용해 웹을 구성하고,
  JavaScript의 이벤트 처리를 통해 동적인 사용자 인터페이스를 구현했습니다.
-  사용자의 편의성과 시각적 일관성을 고려하여 UI/UX 설계 역량을 향상시켰습니다.

#### 예시 이미지
<img width="1920" height="945" alt="rocketpunch" src="https://github.com/user-attachments/assets/25cdbf08-0cb5-47c8-9fe4-19b9845fe1a6" />


#### 실제 클론 코딩 이미지
<img width="1920" height="945" alt="kok_main" src="https://github.com/user-attachments/assets/3e502abd-0c12-4d45-ad3a-3a53134551fd" />


---

## 🗂 ERD (Entity Relationship Diagram)
-  **데이터베이스 구현 능력단위**에서 배운 테이블 설계 및 제약조건 설정 방법을 적용하여
테이블 간의 관계를 체계적으로 구성했습니다.
-  관계 구성 시 정규화를 통해 데이터 중복을 최소화하였고,
   **SQL 활용 능력단위**에서 배운 **DML(INSERT, UPDATE, DELETE, SELECT)** 문법을 사용하여
더미 데이터를 추가·수정·삭제·조회하며 동작을 검증했습니다.
-  이를 통해 데이터 구조 설계부터 실제 조작까지의 전 과정을 경험했습니다.
<img width="8346" height="6562" alt="diagram" src="https://github.com/user-attachments/assets/aabfcb18-6358-4b1d-908a-9b97a2029da9" />


---

## 🔗 공공데이터 API 연동

-  **서버 프로그램 구현 능력단위**에서 배운 Spring Boot를 이용한 RESTful API 구성 방법을 활용해
외부 공공데이터 API(졸업생의 취업현황-일반대학원 API)를 연동했습니다.
-  API 연동 시 **통합 구현 능력단위**에서 배운 데이터 통신 및 연계 기술을 적용하여
실시간으로 데이터를 수집하고 가공·표시했습니다.
-  이를 통해 서버와 외부 시스템 간의 연동 및 데이터 흐름 이해도를 높일 수 있었습니다.


📦 취업률 정보를 위해 졸업생의 취업현황(일반대학원)

제공 기관: [경기데이터드림](https://data.gg.go.kr/portal/mainPage.do), [공공데이터활용](https://data.gg.go.kr/portal/data/service/selectServicePage.do?page=1&sortColumn=&sortDirection=&infId=K2P9SMVB0O4JL6G9J5O524087836&infSeq=1)

주요 기능:

-   학과별 취업률 목록 조회
-   등록일 기준 최신 정보 제공
<img width="1920" height="945" alt="api" src="https://github.com/user-attachments/assets/54b96cd2-2ae4-4e6f-9fb5-8c626d8434a6" />


---

## 👩‍💻 담당 업무

-  **화면 구현 능력단위**에서 배운 JavaScript DOM 제어 및 이벤트 처리 기술을 활용하여
커뮤니티, 기업 목록/상세 등의 인터페이스를 제작했습니다.
-  **서버 프로그램 구현 능력단위**에서 배운 Controller-Service-DAO 구조를 기반으로
백엔드 비즈니스 로직을 구성하고, REST API를 통해 클라이언트와 통신했습니다.

### [Front]

<img width="412" height="248" alt="화면진척도" src="https://github.com/user-attachments/assets/78bcc3ad-4aa1-41f2-875c-4223c1c31c09" />


<br>▶ **메인 페이지(웹)**

-   메인
-   헤더
-   사이드 바
-   404 에러
-   고객지원 창
-   설정 창
-   지원내역 창
-   통합 검색 페이지<br>

▶ **메인 페이지(모바일)**

-   메인
-   헤더
-   푸터

▶ **관리자 페이지(웹)**

-   로그인
-   관리자 등록
-   홈화면
-   회원 목록
-   회원 상세
-   기업 목록
-   기업 상세
-   체험 공고 목록
-   체험 공고 상세
-   인턴 공고 목록
-   인턴 공고 상세
-   광고비 결제 관리
-   체험비 결제 관리
-   광고 목록
-   배너 등록
-   공지사항 목록
-   공지사항 등록
-   신고 게시글 목록
-   신고 게시글 상세

### [Back]

<img width="782" height="171" alt="서버진척도" src="https://github.com/user-attachments/assets/ddd2430f-f5ac-4f33-a142-9a26957de661" />

<br>▶ 커뮤니티 (웹 + 앱)

-   게시글 목록
-   게시글 상세
-   게시글 작성
-   게시글 수정
-   게시글 삭제
-   게시글 신고
-   게시글 좋아요
-   댓글 목록
-   댓글 수정
-   댓글 삭제
-   댓글 작성<br>

▶ 기업 목록

-   기업 목록
-   기업 검색<br>

▶ 기업 상세

-   기업 상세
-   기업 팔로우
-   기업별 체험/인턴 공고 목록
-   기업별 체험/인턴 공고 검색<br>

## 🚨 오류 상황들
-  개발 과정에서 발생한 캐싱 처리, S3 파일 업로드, 권한 제어 등의 문제를 분석 후 로그 추적 및 디버깅을 통해 해결했습니다.
-  이를 통해 실제로 서비스가 돌아가기 위한 백엔드 흐름 을 깊게 이해할 수 있었습니다.

### **📌 1. ERD의 흐름을 정확히 파악하자**

#### **💥문제 상황**
-  AWS S3 Presigner 호출 시 key 값이 null로 확인
<img width="1168" height="314" alt="S3에서 불러오기 실패" src="https://github.com/user-attachments/assets/4745b1ef-c687-404d-9522-ad48e0ec4e36" />

#### **🔍문제 원인**

-   파일 업로드 과정에서 PostFileDTO에는 값이 들어가고 있었으나, FileDTO에는 데이터가 저장되지 않아 S3 Key가 null로 반환되는 문제가 발생했습니다.

#### **🛠️해결 방안**

-   파일 업로드 로직에 **FileDTO 저장 처리를 추가**하고 이후 **PostFileDTO와 매핑**하도록 수정하여 조회 시 정상적으로 `Presigned URL` 을 생성할 수 있도록 개선했습니다.
<img width="528" height="572" alt="매핑오류" src="https://github.com/user-attachments/assets/f7efccf9-cb6e-415a-955c-79ec0acf2f5f" />

### **📌 2. 캐싱 유지 및 무효화 처리를 신경쓰자**

#### **💥문제 상황**
-  게시글 상세 좋아요 수와 게시글 목록 좋아요 수가 불일치하는 오류 발생
<img width="2561" height="1398" alt="localhost_10000_community_page" src="https://github.com/user-attachments/assets/0b1fdfa1-4634-4db7-8b36-3f74e95a8037" />
<img width="2561" height="1398" alt="localhost_10000_community_page (1)" src="https://github.com/user-attachments/assets/43dd2a92-3b13-48eb-9936-1555bd888fa6" />

#### **🔍문제 원인**

-   게시글 상세 조회 시 캐싱해 조회 성능을 개선했으나 좋아요/좋아요 취소 기능에는 **캐시 무효화 처리가 없었습니다**.

#### **🛠️해결 방안**

-   좋아요 관련 service에 `@CacheEvict` 를 적용해 캐시 무효화로 해결했습니다.
<img width="445" height="238" alt="image" src="https://github.com/user-attachments/assets/2497a4f0-f618-4bef-8dc1-2600d241186a" />


## 📊 QA 테스트
-  **애플리케이션 테스트 수행 능력단위**에서 배운 테스트 케이스 설계 및 실행 절차를 기반으로
QA 테스트 문서를 작성하고 기능별 검증을 수행했습니다.
-  **JUnit5를 활용한 단위 테스트 및 통합 테스트**를 통해
애플리케이션의 안정성과 기능 완성도를 검증했습니다.

<img width="503" height="186" alt="bug-fix" src="https://github.com/user-attachments/assets/c1626ec0-fcf7-4257-8fd1-a68f51640dd9" />

---

## 📱 앱 전환 (React Native + WebView)
-  **통합 구현 능력단위**에서 배운 API 통합 및 데이터 관리 기법을 활용하여
React Query 기반의 WebView 환경을 구현했습니다.

-   WebView를 통해 모바일 앱 환경 구현

![mobile](https://github.com/user-attachments/assets/55646403-b6a8-45c3-8d9b-cb6e7cee2ec0)

---

## AWS Cloud 배포

<img width="1920" height="1080" alt="Load-Balancing" src="https://github.com/user-attachments/assets/c9d71278-9e41-4c15-9f51-0766bb7a44b0" />

---

## ✨ 느낀 점
이번 프로젝트를 통해 단순한 CRUD 수준을 넘어 **실제로 서비스가 돌아가기 위한 백엔드 흐름** 을 깊게 이해할 수 있었습니다.  
`AWS, Security, Cache, Presigned URL, Redis` 등 실전 환경에서 자주 사용되는 기술들을 직접 적용하며,  
**문제를 피하지 않고 끝까지 해결하는 과정이 개발자의 기본 역량이라는 것**을 체감했습니다.

특히 서비스는 단순히 기능이 동작하는 것만으로는 충분하지 않으며  
**데이터 무결성과 정합성, 보안 등 여러 가지를 고려해야 진짜 서비스가 된다**는 것을 배웠습니다.  
또한 한 번에 완벽한 코드는 존재하지 않으며, **끊임없는 개선과 검증이 곧 품질**이라는 점도 느꼈습니다.

프로젝트 중도에 불의의 사고로 인해 어려움이 있었지만,
그 과정에서도 끝까지 직접 문제를 해결하며 <br>
**왜 이런 구조가 필요할까? 더 나은 방법은 뭘까?** 를 질문하는 습관이 생겼고,  
이 경험은 앞으로 더 성장할 수 있는 원동력이 되었습니다.  
앞으로는 서비스의 규모가 확장되더라도 **안정적이고 신뢰할 수 있는 서비스**를 설계할 수 있는 개발자로 계속 성장하고자 합니다.

---

📌 **작성자:** 정희준 &nbsp;&nbsp;&nbsp;&nbsp; **TEAM:** KOK <br>
📅 **기간:** 2025.09.24 ~ 2025.10.12 (**총 프로젝트 기간:** 2025.09.24 ~ 2025.10.24)
