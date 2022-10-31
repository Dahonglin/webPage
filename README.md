# 목차
- [달콤커피 x 빽다방 사이트 디자인](#dalcom-x-paik-coffee)
- [모여봐요, 동물의 숲 팬사이트 디자인](#모여봐요-동물의-숲-팬사이트)
- [CGV 영화관 사이트 디자인](#cgv-영화관-사이트)

<br>

# Dalcom x Paik coffee
#### >>> [🌐Dalcom x Paik coffee](https://dahonglin.github.io/webPage/DalPaik_PJ/index.html) <<<
#### 달콤 커피 사이트를 빽다방 IP로 재해석하여 디자인한 사이트
#### [🛠 와이어프레임 보기](https://dahonglin.github.io/webPage/DalPaik_PJ/DalPaik_PJ%EB%B6%84%EC%84%9D%EC%84%A4%EA%B3%84.pdf) | [📚 사이트 설명서 보기](https://dahonglin.github.io/webPage/DalPaik_PJ/%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C-%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4-%EB%B9%BD%EB%8B%A4%EB%B0%A9-%EA%B0%80%EC%9D%B4%EB%93%9C-%EB%AC%B8%EC%84%9C.pdf)

<img alt="JavaScript" src ="https://img.shields.io/badge/JavaScriipt-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=black"/> <img alt="jQuery" src ="https://img.shields.io/badge/jQuery-0769AD.svg?&style=for-the-badge&logo=jQuery&logoColor=white"/> <img alt="HTML5" src ="https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white"/> <img alt="Css" src ="https://img.shields.io/badge/CSS3-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white"/>

<br>

#### 사이트 구현 내용

![image](https://dahonglin.github.io/webPage/DalPaik_PJ/dalpaik_guide1.gif)
<br>

- #### 텍스트 애니메이션
  - [A.O.S 라이브러리](https://michalsnik.github.io/aos/)를 사용하여 자연스러운 텍스트 애니메이션 구현
  - 라이브러리를 사용하여 사이트에 전체적으로 통일감 있는 애니메이션을 적용함.
<br> <br> 

![image](https://dahonglin.github.io/webPage/DalPaik_PJ/dalpaik_guide2.gif)

- #### 마우스 트래킹 모션 이미지
  - 마우스의 움직임에 따라 이미지가 움직이는 애니메이션<br>
  `    let docStyle = document.body.style;
    document.addEventListener('mousemove', (val) => {
        docStyle.setProperty('--mouse-x', val.screenX);
        docStyle.setProperty('--mouse-y', val.screenY);
    });`
  - 마우스의 움직임을 입력받아 css 변경된 수치를 변수로 전달함.

<br>

![image](https://dahonglin.github.io/webPage/DalPaik_PJ/dalpaik_guide3.gif)

- #### 이미지 슬라이드
  - 기본적인 이미지 슬라이드 배너
  - 좌/우 화살표를 통해 이미지를 이동할 수 있으며 일정한 간격으로 이미지가 변경 됨.

<br>

![image](https://dahonglin.github.io/webPage/DalPaik_PJ/dalpaik_guide4.gif)

- #### 음료 이미지 슬라이드
  - 네비게이션 버튼 클릭 시 하단의 음료 이미지가 변경 됨.
  - 선택 된 버튼은 노란색으로 하이라이트 표시
  - 좌측에서 우측으로 음료 슬라이드가 자연스럽게 흘러감.

<br>

![image](https://dahonglin.github.io/webPage/DalPaik_PJ/dalpaik_guide5.gif)

- #### 한글/영어 언어 변경
  - 상단의 KR/EN 버튼 클릭 시 사이트 언어 변경
  - 상단 메뉴 / 메인 텍스트 모두 변경 됨.

- #### 상단 메뉴 스크롤 대응
  - 스크롤 위/아래 움직임에 따라 상단 메뉴 on/off

