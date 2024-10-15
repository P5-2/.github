# 💵 재정 개조단


## 프로젝트 소개
### 재정 개조단: 금융 상품 추천 비교
- 개발 기간: 2024.09.05 ~ 2024.10.15(약 7주)
- 개발 인원: 5인(풀 스택 5인)

### 📈 프로젝트 소개

이 프로젝트는 사용자들이 **다양한 금융 상품을 쉽게 비교**하고 현명하게 선택할 수 있도록 돕는 종합 금융 플랫폼을 만드는 것을 목표로 합니다. 예적금, 펀드 등 여러 자산 상품을 카테고리별로 추천해 주며, 최신 금융 지수와 뉴스를 제공하여 더 나은 투자 결정을 내릴 수 있도록 지원합니다. 또한, 개인의 투자 성향에 맞춘 **맞춤형 상품을 제안**하고, 신뢰할 수 있는 **데이터에 기반한 주간 추천 종목**을 통해 재테크를 최적화할 수 있게 합니다.

### 🎯 프로젝트 목적

1. **투자 결정의 효율성 향상**  
   사용자는 예적금, 펀드 등 다양한 금융 상품을 한눈에 비교하고 추천받을 수 있어, 시간과 노력을 절약할 수 있습니다. 또한, 최신 금융 지수와 뉴스를 실시간으로 제공받아 더 나은 투자 결정을 내릴 수 있습니다.

2. **맞춤형 자산 관리**  
   개인의 투자 성향, 자본, 연령 등의 정보를 바탕으로 최적화된 금융 상품을 추천하여 자산 증식의 기회를 제공합니다. 다양한 자산군을 효율적으로 분석함으로써 리스크를 분산하고, 예상 수익과 수수료 등을 미리 계산하여 신중한 의사결정을 돕습니다.

3. **금융 이해력 향상**  
   금융 퀴즈를 통해 다양한 금융 개념과 용어를 학습할 수 있어 기초 금융 지식을 습득할 수 있습니다. 퀴즈 이벤트를 통해 금융 지식을 재미있고 적극적으로 습득하도록 유도하며, 직관적이고 사용하기 쉬운 인터페이스로 누구나 쉽게 투자 기회를 탐색할 수 있습니다.




## 주요 기능

### 1. 금융 상품 추천 시스템

#### 🌟 Hot 상품 추천
- 사용자가 계산기에 담은 횟수를 기준으로 예적금 상품을 인기 순으로 세 개를 추천합니다.
- 사용자의 관심도를 반영하여 가장 많이 선택된 상품을 우선적으로 제안하는 방식입니다.

#### 🎯 개인 상품 추천
- 투자성향 설문조사를 통해 사용자의 투자 성향과 관련된 정보를 수집합니다. 이를 바탕으로 얻은 키워드와 투자 성향을 활용하여 금융 상품을 필터링한 후, 금리에 따라 내림차순으로 정렬하여 사용자에게 상품을 추천합니다. 이 방식은 사용자의 개인적 특성과 선호도를 반영하여 맞춤형 금융상품을 제공하는 것을 목표로 합니다.

### 2. 즐겨찾기 및 상품 비교

#### 📌 즐겨찾기
- 사용자가 비교를 원하는 금융상품을 즐겨찾기 페이지에 저장할 수 있습니다. 이는 사용자가 관심 있는 상품을 쉽게 관리하고 추후에 다시 검토할 수 있도록 도와줍니다.

#### 📊 상품 비교
- 즐겨찾기 페이지나 상품 리스트에서 최대 세 개의 금융상품을 선택하여 이율을 비교할 수 있습니다. 이를 통해 사용자는 각 상품의 금리를 한 눈에 비교하고, 자신에게 가장 유리한 조건의 상품을 선택할 수 있습니다.

### 3. 계산기

#### 🛒상품 담기
- 사용자는 계산하고 싶은 다양한 금융상품을 계산기에 담아 비교할 수 있습니다. 중복되지 않은 여러 개의 상품을 선택하여 예상 수익을 계산할 수 있습니다.

#### 🧮계산하기
- 담은 상품에 대해 원하는 금액을 투자하고, 몇 개월 후의 결과를 시뮬레이션할 수 있습니다. 각 상품별로 투자 결과를 제공하여 어느 상품이 더 많은 이익을 낼 수 있는지 직관적으로 비교할 수 있게 합니다.

### 4. 금 시세

#### 📈 금 시세
- 사용자가 원하는 날짜의 금 시세와 최신 날짜의 금 시세를 제공합니다.

#### ✨ 금 시세 예측 모델
- DL4J 라이브러리를 사용하여 자바로 LSTM 모델을 구현합니다. 이를 통해 이전까지의 금 시세 데이터를 기반으로 향후 금 시세를 예측하여 사용자에게 제공합니다.

### 5. 💰환율 정보
- 각 외화의 환율 상세 정보를 제공합니다.

### 6. 📋 설문 조사
- 설문 조사를 통해 사용자의 정보를 수집합니다.
- 현재 급여, 자산, 투자 성향 등을 조사하여 키워드 및 점수로 저장하고 이를 바탕으로 맞춤형 추천 서비스를 제공합니다.

### 7. 📰 금융 뉴스
- 경험치를 통해 일정 레벨에 도달하면 금융 뉴스를 이용할 수 있습니다. 설문 조사에서 확인한 투자 성향과 관련된 키워드에 대한 뉴스를 제공합니다.

### 8. 🎯 목표 금액 설정 기능
- 사용자는 목표 금액을 설정할 수 있으며, 원하는 금융상품과 매달 저금 및 기간을 설정하여 해당 목표 금액에 도달하는 기능을 제공합니다.

### 9. 🏆 레벨 시스템
- 각 사용자가 로그인할 때 방문 기록 테이블이 생성됩니다. 이를 통해 매일 방문 여부를 확인하고, 첫 방문 시 경험치를 획득할 수 있습니다.

### 10. ❓ 금융 퀴즈
- 사용자가 알아야 할 금융 상식을 퀴즈 형식으로 제공하여 금융 지식 수준을 높입니다. 객관식으로 제공되어 사용자가 쉽게 접근할 수 있습니다.

### 11. 💡 금융 꿀팁
- 금융감독원이 제공하는 금융상품 관련 유의사항 및 유익한 정보를 꿀팁 형태로 제공합니다. 은행 및 금융투자 관련 꿀팁을 그림으로 제공하여 사용자가 쉽게 이해할 수 있도록 합니다.



## 👨‍👩‍👧‍👧팀원 소개

| 이름   | 역할                                                                    |
|--------|-------------------------------------------------------------------------|
| 구지원 | SNS 로그인(네이버), 펀드리스트 페이지, 즐겨찾기 페이지                    |
| 김기훈 | 금 시세 페이지, 목표 금액 모으기 컴포넌트, 환율 페이지, 추천상품 페이지   |
| 손원   | 메인 페이지, 계산기 기능, 퀴즈 기능                                      |
| 배재유 | 금 시세 페이지, 내 정보 페이지, 설문조사 페이지, 사용자 별 레벨 기능      |
| 장은영 | SNS 로그인(카카오), 예금적금 페이지                                      |


## 🔎 개발 환경

### 🛠 Management Tool
<p>
  <img src="https://img.shields.io/badge/github-6E44FF?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
  <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
  <img src="https://img.shields.io/badge/zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor=white">
  <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
</p>


### 💻 IDE
<p>
  <img src="https://img.shields.io/badge/visual%20studio%20code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white">
  <img src="https://img.shields.io/badge/Intellij%20IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white">
  <img src="https://img.shields.io/badge/mysql%20workbench-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</p>

### 🌐 Frontend
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
  <img src="https://img.shields.io/badge/Pinia-42b883?style=for-the-badge&logo=pinia&logoColor=white">
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
</p>

### ⚙️ Backend
<p>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white">
  <img src="https://img.shields.io/badge/MyBatis-E6322E?style=for-the-badge&logo=mybatis&logoColor=white">
  <img src="https://img.shields.io/badge/DL4J-000000?style=for-the-badge&logo=data-science&logoColor=white">
</p>

### 🗄️ Database
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</p>





## 📝 설계 문서

### 🏛️ 아키텍처 구조

  ![image](https://github.com/user-attachments/assets/e0ff26a6-14e7-4a12-aa9a-9dd097242ff0)
  
  *아키텍처 구조*

### 📊 ERD (Entity-Relationship Diagram)
- MySQL을 활용하여 데이터 모델을 설계하였습니다.
  
  ![erd](https://github.com/user-attachments/assets/9468ef6a-75af-46ee-bd05-71be56085013)

  *ERD*

### 🎨 스토리보드
- Figma를 이용해 사용자 인터페이스와 흐름을 시각적으로 설계하였습니다.
  
  ![storyboard](https://github.com/user-attachments/assets/4abccb6a-f1d8-4eb0-b334-c625ce03ba90)

  *스토리보드*




## 🚀 기능 시연

### 🔐 로그인 및 회원 가입
- **SNS 로그인**
  - 카카오, 네이버 계정을 통해 간편하게 SNS 로그인이 가능합니다.
  - SNS 계정과 연동하여 손쉽게 회원 가입 및 로그인할 수 있습니다.

  ![네이버 로그인](https://github.com/user-attachments/assets/1975063a-7aa6-416f-899b-ae8c91205e8a)

  *네이버 로그인*

  ![카카오 로그인](https://github.com/user-attachments/assets/b3f425c4-a4e8-487d-b9f8-28b2bee1d83e)

  *카카오 로그인*

### 📊 펀드 페이지
- **모든 펀드 상품 조회 가능**
  - 다양한 펀드 상품을 한눈에 확인할 수 있습니다.
- **비교하기 기능**
  - 체크 박스를 이용해 모달 창으로 여러 펀드 상품을 선택하고 비교할 수 있습니다.
- **계산기 아이콘과 하트 아이콘 활용**
  - 계산기 아이콘: 계산기에 담아 예상 이익을 계산할 수 있습니다.
  - 하트 아이콘: 즐겨 찾기에 추가하거나 삭제할 수 있습니다.

  ![fund page](https://github.com/user-attachments/assets/b0dbd307-3623-4e99-9e89-ef976b0d0b66)

  *펀드 페이지*

  ![fund 모달창](https://github.com/user-attachments/assets/e6b5b727-c44a-4b21-8a55-5f41db7db0b6)

  *펀드 모달창*


### ⭐ 즐겨찾기 페이지
- **예금, 적금, 펀드 상품 즐겨찾기**
  - 사용자가 원하는 예금, 적금, 펀드 상품을 즐겨찾기에 추가하여 한눈에 확인할 수 있습니다.
- **상품 별 조회**
  - 예금, 적금, 펀드 탭을 이용해 각 상품을 별도로 조회할 수 있습니다.
- **비교하기 기능**
  - 체크 박스를 통해 여러 상품을 선택하고 모달 창에서 상세 비교가 가능합니다.

  ![like-deposit](https://github.com/user-attachments/assets/2d0ba69c-7be0-46a8-959a-8909c349115d)

  *예금 즐겨찾기 페이지*

  ![like-fund](https://github.com/user-attachments/assets/b2c031a1-6570-46d8-8955-2e71105a1e69)

  *펀드 즐겨찾기 페이지*

  ![like-savings](https://github.com/user-attachments/assets/0e85b80d-6238-4c82-a7ac-41660b371c64)

  *적금 즐겨찾기 페이지*


### 🏠 메인 페이지
- **예금, 적금, 펀드 Hot 3 상품**
  - 사람들에게 가장 인기있는 금융상품 세 가지를 추천해줍니다.

  ![HotItemList](https://github.com/user-attachments/assets/f88475f3-df82-42f5-8893-c5d0051d4441)

  *금융상품 Hot 3*

- **금융꿀팁**
 - 금융감독원이 알려주는 은행·금융에 관한 유의사항, 유익정보와 같은 꿀팁을 알려줍니다.
 ![financeTip](https://github.com/user-attachments/assets/026ff264-d645-4071-a8f0-4cba66800c12)

 *금융꿀팁*


### 🔍 상세 페이지
- **금융상품 페이지**
  - 선택한 금융상품의 상세정보를 확인할 수 있습니다.

  ![예적금상세](https://github.com/user-attachments/assets/a1741622-c821-4cac-b0bd-8ac30de0a667)

  *예적금 상세 페이지*

  ![펀드상세](https://github.com/user-attachments/assets/5d511141-c2f7-4b0e-a5bb-5265ebf2ab74)

  *펀드 상세 페이지*

### 🧮 계산기 기능
- **계산기에 상품 담기**
  - 계산하고 싶은 상품을 중복되지 않게 담을 수 있습니다.
- **상품 계산하기**
  - 담은 상품에 원하는 금액을 투자하여 미래 수익을 계산할 수 있습니다.

  ![담기](https://github.com/user-attachments/assets/732f9282-2fe8-491d-9687-6e73a20f6e67)

  *계산기 상품 담기*

  ![계산하기](https://github.com/user-attachments/assets/00fe459c-8d87-4e8f-a98b-605c6e1c6ea0)

  *계산하기*

### ❓ 퀴즈 기능
- **총 42가지의 퀴즈**
  - 42개의 퀴즈중 랜덤으로 매일 하나 씩 제공합니다.
  - 객관식 금융 퀴즈를 통해 금융 상식을 늘릴 수 있습니다.

  ![퀴즈](https://github.com/user-attachments/assets/884cca3b-8659-4d7a-89c4-a85e4c4e7f98)

  *퀴즈*
  
### 💰 환율 조회 페이지
- **주요 환율 3종 상단 하이라이트**
  - 통화량이 많은 주요 통화 3종의 시세를 손쉽게 파악할 수 있습니다.
- **전체 통화 확인 기능**
  - 전체 통화를 하단의 표로 확인할 수 있습니다.
    
  ![외화1](https://github.com/user-attachments/assets/2a531b7c-e064-4f9e-9d73-62c72f840c6d)
  
  *외화 상단 하이라이트*


### 👍 추천 페이지
- **예금, 적금, 펀드 상품 추천**
  - 사용자의 금융 환경에 따라 필터링된 상품을 확인할 수 있습니다.
- **상품 별 조회**
  - 예금, 적금, 펀드 토글 버튼을 이용해 각 상품별로 조회할 수 있습니다.
    
  ![추천1](https://github.com/user-attachments/assets/52965efa-6638-47b8-8e05-ce5c4855bbf4)
  
  *추천 페이지 토글*

  ![추천3](https://github.com/user-attachments/assets/afb0e49a-3535-4e98-a5d7-c45dbc550b62)
  
  *추천 키워드 확인*

### 설문조사 페이지 📋
![설문조사](https://github.com/user-attachments/assets/a3b4aa77-352e-4fb1-9336-e193f8db1196)

- **투자 성향 분석** 💡
  - 설문지에 매긴 점수를 기반으로 **투자 성향 분석**을 실시합니다.


- **설문조사 진행 방법** 📝
  - 페이지네이션을 통해 설문조사를 단계별로 진행합니다. 📊


- **선택지 저장 및 상품 추천** 🎁
  - 선택지에 따른 키워드를 회원 정보에 저장하여 **상품 추천**에 사용합니다. 🔍

  
### 내 정보 페이지 📄
![image](https://github.com/user-attachments/assets/2def2465-9e29-4144-a0d7-689819917876)

- **레벨시스템!** 🎉
  - 각 페이지에 매일 첫 방문 시, **금융 용어 퀴즈**를 맞출 시 경험치를 획득할 수 있습니다. 🏆

- **투자 성향** 📊
  - 투자 성향 조사에서 확인한 투자 성향을 확인할 수 있습니다. 🔍

- **금융 뉴스** 📰
  - **레벨 2 이상**부터 사용자의 투자 성향에 맞는 키워드에 따른 금융 뉴스를 제공합니다. 🌐

### 🎯 목표 금액 모으기 기능
- **예적금 상품으로 모으기**
  - 사용자가 입력한 모으기 목표와 금액으로 달성도를 파악할 수 있습니다.
- **거래 내역으로 입금 기록 최신화**
  - 거래 내역에서 통장에 입금된 기록을 제공받아 통장 내역을 최신화 할 수 있습니다.

    
  ![예적금으로모으기2](https://github.com/user-attachments/assets/7cab592e-33ac-4e21-949a-b056bc912325)
  ![모으기3](https://github.com/user-attachments/assets/317abb42-f6a3-4535-9ddc-6c8bfe22cd56)
  
  *모으기 통장 설정*

  ![예적금으로모으기1](https://github.com/user-attachments/assets/4fb0f7e8-f9ad-495e-8d3e-3a27cfb303a4)
  
  *입금 금액 확인*

  
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
