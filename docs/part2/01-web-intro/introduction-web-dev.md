# 웹 개발방법의 소개

![](http://www.marshsoftware.com/wp-content/uploads/2016/05/worldwideweb.jpg)
> 그림 출처: [http://www.marshsoftware.com/web-development/](http://www.marshsoftware.com/web-development/)

웹(Web) 개발을 이야기 하기 전에 웹이란 무엇인가를 먼저 생각 해봅니다. 웹(Web)이란 `월드 와이드 웹 (World Wide Web)`의 줄임말로 www 라고 부르기도 합니다. 사실 이미 너무나 많이 사용하고 있고 쉽게 접할 수 있기 때문에 이제는 특별한 설명이 없어도 웹이라는 것을 느끼고 사용하고 있습니다.

그럼 웹 개발은 무엇일까요?

웹 개발이란 이러한 웹을 제공하기 위한 요소들을 만드는 SW 개발입니다. 웹을 위한 요소는 대표적으로 `클라이언트 - 서버`가 있습니다. 이러한 요소를  `Front-end - Back-end`라고 부릅니다.

항목 | Front-end | Back-end
--- | --- | ---
아키텍처 | 클라이언트 | 서버
프로그램 | 웹 브라우저 | 웹 서버
기능 | 웹 서버로 요청 (Request)를 전달 | 요청 (Request)를 수신받아서 처리 후 응답 (Response)를 반환
 | UI를 Display 처리 | Biz 로직 및 DB 연동 등의 처리

Front-end, Back-end를 구분하여 프론트-엔드 개발자, 백-엔드 개발자라고 부르고 Front/Back-end를 모두 사용할 줄 아는 개발자는  풀스택 개발자(Fullstack Developer)라고 부릅니다.

## 왜 Front-end, Back-end인가?

왜 Front-end, back-end로 개발하게 되었을까? 물론 기능이 다르기 때문이지만 가장 큰 이유는 개발 언어의 차이에서 발생하였다고 생각됩니다.

* Front-end: html, css, javascript
* Back-end: asp, php, jsp

과거(몇 년 전이지만)의 구분이 현재까지 이어지고 있습니다. 하지만 기술적으로는 현재 Back-end 구현 시에도 Node.js를 이용하면 Javascript만으로도 구현이 가능한 시대입니다. 즉, 기술로 Front-end와 Back-end를 구분하는 목적은 이제 사라졌습니다. 그런데도 왜 사람들은 굳이 구분을 할까 생각하였는데, 기술이 발전하며 더욱 전문화 되었기 때문에 구분이 유지되고 있다고 생각합니다.

처음에는 웹 퍼블리서라고 하며 디자인된 화면을 Markup, css를 구성하기 때문에 기술적 난이도가 낮다고 판단하였지만 현재는 다양한 UI/UX를 제공하기 위해 기술적 수준이 매우 높아졌고 Front-end 개발자라는 전문화된 트랙으로 구분이 되어가고 있다고 생각됩니다. 또한 Back-end 개발자들도 분산처리부터 대용량 자료 처리를 위한 전문적인 기술들을 숙련함에 따라 더욱 전문화 되고 있습니다.

그런데도 이 걸 다하는 풀스택 개발자는 대단합니다.

* Front-end: html, css, sass, stylus, javascript, webpack, react, vue, d3 ...
* Back-end: python, java, scala, golang, c#, c/c++, php ...

이렇게나 많은 개발 언어와 기술들이 존재합니다.

하지만 이렇게 Front/Back-end를 구분지어서 역할을 나누는 것은 책임을 회피하는 방법이라고만 생각됩니다. 프로그래머라면 Back-end, Front-end 구분없이 대략적인 지식을 알고 있어야 효과적인 협업을 할 수 있다고 생각됩니다. 그래서 본 스터디의 목적은 Front-end ~ Back-end까지 전체 내용에 대해서 스터디를 하며 이해하는 것이 그 목적입니다.

## 그래서 어떻게 만드는 것이더냐!

