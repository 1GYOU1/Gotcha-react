# Gotcha-project

### 2. Gotcha-React version

 - React.js 라이브러리 사용하여 캡슐 뽑기 구현

<br>

### MainPage View

![ezgif com-gif-maker](https://github.com/1GYOU1/Javascript/assets/90018379/e423444a-98cc-410d-af47-8427cb57ea13)

![turn2](https://github.com/1GYOU1/Javascript/assets/90018379/7e0e79c3-eac0-452e-ad48-b52548b60cf0)

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-F68212?style=flat-square&logo=CSS3&logoColor=white"/>
<img src="https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=Sass&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/>

<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/>

<img src="https://img.shields.io/badge/Adobe Photoshop-31A8FF?style=flat-square&logo=Adobe Photoshop&logoColor=white"/>
<img src="https://img.shields.io/badge/Adobe Illustrator-FF9A00?style=flat-square&logo=Adobe Illustrator&logoColor=white"/>

<br>

### 주요 기능
- 인트로 애니메이션
- 캡슐 뽑기 애니메이션
- 동전 드래그 앤 드롭
- 인벤토리 창
- 퀴즈 맞추기

<br>

### Github Page : https://1gyou1.github.io/Gotcha-react

<br>

### Gotcha-React App을 사용하기 전 행동 수칙

> npm start

> npm install react-router-dom

<br>

### 프로젝트 진행 과정

2023년 6월 5주차
- React 세팅(완료 ✔︎)
- Intro.js
    - 애니메이션 반응형 수정 (완료 ✔︎)
    - 애니메이션 후 Start.js 컴포넌트로 자동 랜딩 (완료 ✔︎)
- Header.js
    - Start.js에서 부터 고정 노출 (완료 ✔︎)
- Start.js
    - 버튼 클릭 시 애니메이션 추가 (완료 ✔︎)
    - 버튼 클릭 시 일정 시간 후 Main.js 컴포넌트로 랜딩 (완료 ✔︎)

2023년 7월 1주차
- Main.js
    - (1) 초반 진입 업데이트 변수 정리, 업데이트 (완료 ✔︎)
    - (2) 랜덤 결과(랜덤 배열 생성) (완료 ✔︎)
    - (3) 캡슐 통 이미지 생성, 이미지 업데이트 (완료 ✔︎)
    - (4) 동전 드래그 이벤트 (완료 ✔︎)
    - (5) 동전 넣는 영역에 진입했는지 체크 (완료 ✔︎)

2023년 7월 2주차
- Main.js
    - (6) 넣은 동전 카운트 (완료 ✔︎)
    - (7) 동전 위치 초기화 (완료 ✔︎)
    - (8) 캡슐 뽑기 애니메이션 실행 (완료 ✔︎)
    - (9) 출구에 뽑은 캡슐 이미지 노출 (완료 ✔︎)
    - (10) 뽑은 캡슐 딤처리 (완료 ✔︎)
    - (11) 딤처리에 뽑은 캡슐 이미지 노출, 캡슐 오픈 결과 이미지로 변경 (완료 ✔︎)
    - (12) 오픈 후 이어서하기 버튼 생성 (완료 ✔︎)
    - (13) 캡슐 오픈 후 값 업데이트, 딤처리 해제, 뽑기 캡슐 이미지 제거(이어서 뽑기) (완료 ✔︎)
    - (14) 인벤토리 팝업 오픈, 딤처리 (완료 ✔︎)
    - (15) 인벤토리 팝업 리스트 생성, 플레이(뽑기) 횟수에 따라 결과 이미지 변경 (완료 ✔︎)
    - (16) 인벤토리 팝업 닫기, 딤처리 해제 (완료 ✔︎)

2023년 7월 3주
- Main.js
    - 퀴즈 리스트 팝업
        - (17) 리스트 팝업 오픈, 딤처리 (완료 ✔︎)
        - (18) 리스트 팝업 li 생성 (완료 ✔︎)
        - (19) 리스트 팝업 닫기 (완료 ✔︎)
    - 퀴즈 문제 풀이 팝업
        - (20) 문제 풀이 팝업 오픈 (완료 ✔︎)
        - (21) 문제 풀이 팝업 제목, 문제, 정답 리스트 생성 (완료 ✔︎)
        - (22) 문제 풀이 정답 체크
            - 선택한 문제 리스트 li에 class off 추가 (완료 ✔︎)  
            - 정답이면 동전 추가 지급 (완료 ✔︎) 
        - (23) 문제 풀이 팝업 닫기, 딤처리 제거 (완료 ✔︎)

2023년 7월 4주차
- Main.js
    - 리셋 (완료 ✔︎)
    - 컴포넌트 분리
        - 퀴즈 팝업 Quiz.js (완료 ✔︎)
        - 인벤토리 팝업 Inventory.js (완료 ✔︎)
    - 값 업데이트 점검 (완료 ✔︎)
    - UI 개선 화살표 추가, css 수정 (진행중 ~)

<br>

---
### 1. Gotcha-vanilla version
 - 순수 바닐라 자바스크립트로 캡슐 뽑기 구현

 vanilla.js 버전 이어서 보기 -> https://github.com/1GYOU1/Gotcha