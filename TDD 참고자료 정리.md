## TDD 참고자료 정리

* 아래의 자바스크립트 정보와 유튜브 동영상을 확인하면 자바스크립트로 구현한 것을 자바나 다른 언어로 구현하면서 TDD 에 대한 실습이 가능할 것으로 판단된다. 실습은 내용을 좀더 숙지한 이후에 안드로이드 스튜디오에서 해보자!

### 자바스크립트 TDD

1. [도전! JavaScript TDD – 1. 시작](http://huns.me/development/716)
    - 가장 먼저 문제를 명세로 정의하고, 명세로 정의한 내용을 테스트 코드로 표현한다. 그리고 그 문제를 풀어내는 코드를 구현하는 것
    - TDD의 테스트 명세는 개발자 관점이 아닌, 사용자 관점에서 작성
2. [도전! JavaScript TDD – 2. TDD 리듬](http://huns.me/development/823)
    - 사이드 이펙트를 만들었을 경우 원인을 잘 모르겠다면 일단 코드를 테스트 통과 가능한 이전 상태로 되돌려놓고 문제를 다시 풀어가는 게 좋다.
    - 리팩토링은 반드시 모든 테스트가 통과인 상태일 때만 진행해야한다.
3. [도전! JavaScript TDD – 3. 점진적 명세 작성](http://huns.me/development/939)
    - 첫 번째, 당장 해결해야하는 문제의 범위를 좁힐 수 있기 때문에 문제를 훨씬 쉽게 풀어나갈 수 있다.
    - 두 번째, 사용자 관점에서 애플리케이션의 행위를 바라보기 때문에 외부로 공개하는 인터페이스를 자연스럽게 추상화 할 수 있다.


### 안드로이드 TDD 

1. [Android Studio에서 Unit Testing 적용하기 1](https://davidhyk.github.io/blog/applying-unit-testing-on-android-studio-part1)
    - Test Code에서 Mock Object 사용하기
    - Local Unit Test 전부를 한 번에 실행하는 방법
2. [Android Studio에서 Unit Testing 적용하기 2](https://davidhyk.github.io/blog/applying-unit-testing-on-android-studio-part2)
    - _ActivityTestRule 사용법을 중심으로_





