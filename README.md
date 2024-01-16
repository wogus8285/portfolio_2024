# 나를 '재현'하다 - 웹페이지 소개

## 소개

이 프로젝트는 웹사이트를 통해 '재현'하는 것을 목표로 합니다.

메인화면의 슬라이드를 통하여 제가 만든 작업물에 접근할 수 있으며, 메뉴바를 통해서 저의 프로필과 저를 소개하는 영상 등의 컨텐츠에 접근하실 수 있습니다.

다양한 컨텐츠로 '박재현'이라는 사람을 '재현'해보았으니, 지루하지 않아 하셨으면 좋겠습니다!

## 웹페이지 목록

### 1. 재현북스 웹사이트

- **프로젝트 유형:** 웹사이트
- **디자인 및 코드 링크:**
  - [Figma 디자인](https://www.figma.com/file/XDWYIJ9wtS0NZDpXky67Mq/JaehyunBooks?type=design&node-id=8%3A2&mode=design&t=fQ8kCLO3xZk4m2ji-1)
  - [GitHub 코드](https://github.com/wogus8285/Jaehyun_books)
- **웹사이트 링크:** [재현북스](http://wogus8285.dothome.co.kr/Jaehyun_books)

### 2. 부산엑스포 리뉴얼 웹사이트

- **프로젝트 유형:** 웹사이트 리뉴얼
- **디자인 및 코드 링크:**
  - [Figma 디자인](<https://www.figma.com/file/jqHrK3sqip8VEs3JW70jSk/Busan_Expo(copy)?type=design&node-id=0%3A1&mode=design&t=UrRKuEMMcNamrfEV-1>)
  - [GitHub 코드](https://github.com/wogus8285/BusanExpo)
- **웹사이트 링크:** [부산엑스포](http://wogus8285.dothome.co.kr/Busan_Expo)

### 3. 삼성화재 클론 웹사이트

- **프로젝트 유형:** 클론 웹사이트
- **디자인 및 코드 링크:**
  - [Figma 디자인](<https://www.figma.com/file/z3jJqG0JTjrSCwRbiySnON/Samsungfire(copy)?type=design&node-id=0%3A1&mode=design&t=Lp7v2q541KV2qlZ7-1>)
  - [GitHub 코드](https://github.com/wogus8285/samsungfire)
- **웹사이트 링크:** [삼성화재](http://wogus8285.dothome.co.kr/samsungfire)

## 웹 기술

- HTML
- CSS
- JavaScript (JQuery 사용)

## 디자인 기술

- 포토샵
- 일러스트
- 프리미어 프로
- 피그마

## 특징

### Main

- Swiper 플러그인 사용하여 수직 방향으로 슬라이드되는 웹 페이지
- 각 섹션은 나만의 사이트, 리뉴얼한 사이트, 클론한 사이트, 앱 디자인에 대한 소개와 링크를 제공

### Work

- Diplay : grid를 활용하여 내 작업물을 list 형태로 나열.
- 각 list에 호버를 하면 작업물에 대한 상세한 설명을 볼 수 있음.

### Profile

- 슬라이드를 통하여 다양한 나의 모습에 대하여 소개하는 공간.

### Video

- 프리미어 프로를 활용하여 만든 동영상으로 나 스스로를 재현함.

## 사용된 코드

- Main
  ```
  <!-- Swiper 세로 방향 슬라이드 -->
  const swiper = new Swiper('.swiper', {
  direction: 'vertical',
  loop: true,
  mousewheel: {
  enabled: true,
  }
  })
  ```
