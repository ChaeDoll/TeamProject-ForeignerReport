![header](https://capsule-render.vercel.app/api?type=transparent&height=300&section=header&text=Foreigner%20Report&fontSize=90&fontColor=003399)  

# 서울시 외국인 인프라 개선을 위한 보고서

<br>  

## 📄프로젝트 소개📄
- 개요 : 2023-2 데이터마이닝 및 시각화 (전공) 팀 프로젝트
- 기간 : 2023.10.20 ~ 2023.12.06
- **프로젝트 목표** : 외국인 거주자의 증가로 인프라 개선을 위한 데이터 분석을 통해, 외국인들이 몰리는 지역 식별 및 인프라 구축제안
- **기대효과** : 한국 내 거주하는 외국인들의 삶의 질 향상과 한국에 대한 외국인들의 인식 개선,
  부가적으로 새로운 관광지 개설과 이에 따른 관광객 유치 등의 요소까지 기대 가능

<br>  

## 👥프로젝트 참여자👥
- 총 3명의 팀원으로 구성 되었음
- *자료조사 : 박OO, 최OO*
- *<b>데이터 전처리 : 임채윤</b>*
- *<b>그래프 시각화 : 임채윤</b>*
- *지도 시각화 : 박OO*
- *<b>머신러닝 구현 : 임채윤</b>*
- *<b>코드 정리 : 임채윤</b>*
- *PPT 제작 및 발표 : 최OO*

<br>

## ⚙사용 기술 (언어, 도구)⚙
### Language And Tool
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white"/>
- DataBase : Notion API (https://well-macaroni-835.notion.site/CockTell-DataBase-d0118987948a4e8c883822e12d0dd60b?pvs=4)
  
<br>

## 구현 사항
### FrontEnd
  - 메인 홈페이지 React-swiper 사용하여 구현  

    **배너**
    
    ![1](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/3a3b62f1-dfd8-42dc-8ffc-61690c372156)  
    **레시피 미리보기, 커스텀 미리보기, 칵테일 재료 미리보기**
    
    ![2](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/f7fd3a1d-cfcf-473c-94e4-74f5ffd7f265)
    
  - 레시피 목록 페이지

    **레시피 페이지 더보기 기능**
    
    ![3](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/606821d1-b417-451a-9a0d-514d349324db)  
    
  - 레시피 상세페이지  
    
    **레시피 상세페이지 링크 클립보드로 공유 기능**
    
    ![4](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/28d7314b-982c-45ed-b068-4620b3321e18)


  - 칵테일 알코올 도수 계산기 구현
    
    ![5](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/b1929b0c-903b-4937-8e00-79718919ed0b)
    
  - 자체 회원가입 구현
    
    **회원가입 유효성 검사 기능 구현 (비밀번호 안전도, 닉네임 중복)**
    
    ![6](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/1759ebbd-aa71-42de-99fe-9529980adc3e)
    
- BackEnd
  - Notion API를 사용한 데이터베이스 구축
    - **유저 데이터 베이스**  
      <img src="https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/1c4ef3b6-7b1f-4c64-9e4a-533190d7a905" width="70%"/>
    - **칵테일 데이터 베이스**  
      <img src="https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/d6aa72c7-cb8d-4f8d-b0b2-a802c9ff0fd9" width="40%"/> <img src="https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/80ce88c9-7c7a-44ba-b6b4-4e5e5c91cfae" width="40%"/>
    - **재료 데이터 베이스**  
      <img src="https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/d3d94caf-7673-4645-aa52-379dd7909ff6" width="30%"/> <img src="https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/a2db80f1-b7a6-4253-95a5-cf1ebf099241" width="30%"/> <img src="https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/aca6b30a-7c74-4f74-8b5c-17c3ecc15718" width="30%"/>

  - 데이터베이스 가져오는 API 구현
    - Notion API 사용하여 유저, 칵테일, 재료 데이터 가져오기 (fetch)
      
  - Open Ai API를 사용한 칵테일 AI 추천서비스 구현  
    ![1](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/5ceb2848-c14e-49ab-a82f-2bc13fa0a6a2)

- FullStack
  - **레시피 목록 필터링 기능 구현 (술, 난이도, 도수, 맛)**  
    ![2](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/1f883dc3-b024-434f-853b-5ac23ab1cec7)

  - **레시피 검색 기능 구현 (칵테일 이름, 설명, 맛, 재료 등)**  
    ![3](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/7e373ab4-5c03-40b8-b981-4cdfbca0885f)

  - **가지고 있는 재료를 체크하여 제작 가능한 레시피를 찾는 '나의 냉장고' 페이지 구현**  
    ![4](https://github.com/ChaeSoGong/TeamProject-Cocktell/assets/108540812/5bafd715-16ba-4fa4-84b9-72478db8a190)

<br>
  
## 라이브러리
- 데이터
  - Numpy
  - Pandas
- 그래프 그리기
  - Matplotlib pyplot
  - Seaborn
  - Plotly express
- 지도 그리기 
  - Folium
- 머신러닝 활용
  - Scipy
  - Sklearn
  
<br>

## 프로젝트 실행방법
1. Github에서 data폴더와 code.ipynb 파일을 모두 다운로드 받는다.
2. Jupyter Notebook 환경에서 code.ipynb를 실행시켜 python 코드로 작성된 프로젝트를 열람한다.  

> 이 프로젝트에 기재된 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
