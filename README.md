# kotlin-racingcar

## 4단계 - 자동차 경주(우승자)

### 요구사항 

* 모든 로직에 단위 테스트를 구현한다. 단, UI(System.out, System.in) 로직은 제외
* 핵심 로직을 구현하는 코드와 UI를 담당하는 로직을 구분한다.
* UI 로직을 InputView, ResultView와 같은 클래스를 추가해 분리한다.
* indent(인덴트, 들여쓰기) depth를 2를 넘지 않도록 구현한다. 1까지만 허용한다.
* (예를 들어 while문 안에 if문이 있으면 들여쓰기는 2이다.)
* 힌트: indent(인덴트, 들여쓰기) depth를 줄이는 좋은 방법은 함수(또는 메소드)를 분리하면 된다.
* 함수(또는 메소드)의 길이가 15라인을 넘어가지 않도록 구현한다.
* 함수(또는 메소드)가 한 가지 일만 잘 하도록 구현한다.
* 기능을 구현하기 전에 README.md 파일에 구현할 기능 목록을 정리해 추가한다.
* git의 commit 단위는 앞 단계에서 README.md 파일에 정리한 기능 목록 단위로 추가한다.

### TODO

1. 인스턴스 변수를 private으로 구현한다.
2. 상수를 적절한 위치로 이동시킨다.
3. 객체에 메시지를 보내라는 원칙에 따라 구현한다.
4. 단위 테스트하기 쉬운 구조로 변경한다. (java reflection을 사용하지 않는다.)
5. 핵심 로직과 View 로직을 분리한다. (두가지 로직이 합쳐져 있는 경우 코드 재사용 및 테스트하기 어렵다.) 
