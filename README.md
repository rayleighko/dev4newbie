# doMemorize 🧠
이해하지 못하면 외워라! for Junior Web FE(Front-end) Engineer.

## 들어가기 전에 ✋

이 레포지토리는 Junior FE Engineer가 알면 좋을 내용에 대해 작성되고 있습니다. 참고하시기 전에 [서문](INTRODUCTION.md)을 읽으시면 글을 읽고, 기여하는 데 도움이 됩니다. 더불어 Web FE가 아닌 다른 분야의 가이드를 작성하고 싶으시다면 'fork_me' 브랜치를 참고하세요(뼈대 - 2019. 04. 기준).

## 방식

기본 베이스: 주제 별 꼭 알아야 할 기본 문서만 작성, 추가적으로 보면 도움될 자료에 대한 추천 첨부.

목차 나열 후 각 문서 작성, 문서 작성 이후에는 목차와 링크 연결(목차에 해당하는 디렉터리 이름의 README.md 파일).

## 소개

많이들 이야기하는 '잘하는 개발자'란 무엇일까. 애초에 '잘하는'이라는 단어가 성립하는가. 그에 대한 이야기는 100명의 개발자를 통해 100가지 이야기로 들을 수 있을 것이다. "이렇고 저렇고 하는 개발자가 잘하는 개발자지" 혹은 "잘한다는 걸 어떻게 측정해? '일' 잘하는 개발자는 있겠지만, '개발' 잘하는 개발자가 있을까?"라는 반응이 있을 수도 있다.

이 글을 작성하는 필자는 후자에 가깝다. 필자가 생각하는 '개발자'는 글을 쓰는 사람이다. 비즈니스적인 문제를 기술적으로 해결하기 위해 프로그래밍 언어를 사용해 비즈니스에 대한 '기술에 대한 명세'를 작성하는 사람이라고 말할 수도 있다. 이런 관점에서 보면 '개발'은 '글'을 쓰는 작업이다. 

이제 생각해보자. '글'을 잘쓰는 걸 어떻게 평가할 것인가? 이에 대해 필자가 내린 결론은 '개발 능력은 측정할 수 없음'이다. 그렇다면 필자가 생각하는 '일' 잘하는 개발자는 어떨까? 그것은 측정할 수 있다. 왜냐하면 '개발 능력'이라는 추상적인 것이 아닌 '일'이라는 객관적인 지표, 그러니까 우리가 일반적인 상황에서 느끼기에도 "이 사람은 일을 잘하는 사람이다"라는 전제는 분명 존재하기 때문이다.

그래서 이 레포지토리에서는 필자가 생각하는 '일' 잘하는 개발자란 무엇인지를 알아보고자 한다. 개발을 잘한다고 하면 대부분 단편적으로 구현을 잘하는 사람이라고 생각하기 쉽다. 하지만, '개발'이라는 분야는 누구든 쉽게 접근할 수 있는 전문직이라는 메리트가 있지만, 그만큼 많은 이들이 포기하고 학습을 게을리하는 순간 벽에 부딪힌다는 특성이 있는만큼 그 분야가 매우 방대하다. 누구든 부푼 기대를 가지고 시작할 수는 있지만, 그 끝이 창대하리라는 보장이 없는 것이다.

우선 기본적으로 이 레포지토리에서는 '개발'을 잘하는 개발자는 존재하지 않는다고 가정한다. 우리가 앞으로 이야기할 '잘하는'의 기준은 '개발'이 아닌 '일'에 집중될 것이다. 그러니 '개발'을 잘하고 싶은 사람은 다른 레포지토리를 찾아보시라 말하고 싶다.

이 레포지토리를 참고하기 전에 대략적으로나마 필자가 생각하는 잘하는 개발자에 대해 소개하고자 한다. 그 개발자는 협업을 잘한다. 동료를 생각하고, 어떻게 하면 동료들이 편하게 일할 수 있을지를 고민한다. 그러기 위해서 그는 코드를 간결하고 단순하고 일률적으로 작성한다. 더불어 중복을 피하고자 캡슐화와 추상화를 고민한다. 필자가 목표로 하는 개발자는 이런 개발자를 말한다.

이런 개발자는 PS(Problem Solving), CS(Computer Science)는 기본적인 부분만 외우고 있으며 심화적인 내용은 들으면 이해하거나 기억을 더듬어 자료를 찾아보면 알 수 있는 수준의 개발자를 말한다. 그러니 앞으로의 내용은 이렇게 '일' 잘하는 개발자에 대한 이야기가 될 것이다.

이 글을 읽고 누군가는 동기를 얻어갈 수도 있고, 지식을 얻어갈 수도 있을 것이다. 더불어 누군가는 불편하거나 위기의식을 느낄 수도 있고 화가 날 수도 있다. 만약 그대가 어떤 감정을 느꼈다면, 이 레포지토리가 '오픈소스'라는 것을 기억하시라. 이 레포지토리는 누구든 자유롭게 수정, 배포, 공유할 수 있으니 그대가 느끼는 그 감정 그대로 이 레포지토리를 수정하면 된다.

> 그래서 누구든 자신이 생각하는 '잘하는 개발자'의 기준에 맞게 이 레포지토리를 수정해도 무방하다. 그러기 위해 만드는 것이기도 하기 때문이다.
>
> 추가적으로 아래의 목차는 커리큘럼을 나타낸 것은 아니다. 누구든 궁금한 것이 있다면, 각각의 주제를 참고하면 된다. 물론, 글의 연속성을 위해 조금은 필자가 생각하는 학습 루트로 목차가 구성되겠지만 말이다.


### 목차

* [PS(Problem Solving)](PS/)
  * Coding Test Tips(작성중)
  * [How to study Problem Solving?](https://subinium.github.io/how-to-study-problem-solving/?fbclid=IwAR21WCilS9SjMn0gSnOVDXacamezu2LT-pa2FWBa7IB3FByuMRCjoyQD_Io)
* [CS(Computer Science)](CS/)
  * Common(작성중)
  * Data Structure(작성중)
  * Network(작성중)
  * Operating System(작성중)
  * Database(작성중)
  * Design Pattern(작성중)
* [WEB](WEB/)
  * HTML(작성중)
  * CSS(작성중)
  * Javascript(작성중)
  * Advanced Typescript(작성중)
  * Web UI Tools(작성중)
  * Advanced React(작성중)
  * Web Browser(작성중)
  * Advanced Chrome Dev tools(작성중)
* [ETC](ETC/)
  * English(작성중)
  * Web related Open source(작성중)
  * Cloud for FE(작성중)
  * Docker(작성중)
  * NginX(작성중)
  * [front-end-handbook-2019](https://frontendmasters.com/books/front-end-handbook/2019/)

