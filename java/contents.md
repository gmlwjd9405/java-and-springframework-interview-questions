**:seedling: Java ・ Spring Framework와 관련된 기술 면접에 대비하기 위해서 기본 개념을 정리하는 Repository 입니다.**
<br> 각 항목에 대한 구체적인 내용과 그림을 함께 이해하고 싶으시면 내용 설명 아래에 <span style="background-color: #e1e1e1">관련 POST</span> 를 참고하시면 됩니다.

# 1. Java
## <span style="color:#7E1107">이론</span>

#### java 프로그래밍 이란

#### java와 c/c++의 차이점
- java와 c/c++의 가장 큰 차이점은 실행 환경이다.
- java에서의 개발: 컴파일 혹은 컴파일 + jar압축
  - 자바는 링크 과정이 없이 컴파일러가 바로 바이트 코드를 생성
- c/c++에서의 개발: 컴파일 + 링크

> - []()

#### java언어의 장단점
> - []()

#### java의 접근 제어자의 종류와 특징
![](/images/access-controller.png)


#### OOP의 4가지 특징
1. 추상화
* 구체적인 사물들의 공통적인 특징을 파악해서 이를 하나의 개념(집합)으로 다루는 것
2. 캡슐화
* 정보 은닉(information hiding): 필요가 없는 정보는 외부에서 접근하지 못하도록 제한하는 것
3. 일반화 관계
* 여러 개체들이 가진 공통된 특성을 부각시켜 하나의 개념이나 법칙으로 성립시키는 과정
4. 다형성
* 서로 다른 클래스의 객체가 같은 메시지를 받았을 때 각자의 방식으로 동작하는 능력
> - [https://gmlwjd9405.github.io/2018/07/05/oop-features.html](https://gmlwjd9405.github.io/2018/07/05/oop-features.html)

#### OOP의 5대 원칙 (SOLID)
* **S**: 단일 책임 원칙(SRP, Single Responsibility Principle)
  * 객체는 단 하나의 책임만 가져야 한다.
* **O**: 개방-폐쇄 원칙(OCP, Open Closed Principle)
  * 기존의 코드를 변경하지 않으면서 기능을 추가할 수 있도록 설계가 되어야 한다.
* **L**: 리스코프 치환 원칙(LSP, Liskov Substitution Principle)
  * 일반화 관계에 대한 이야기며, 자식 클래스는 최소한 자신의 부모 클래스에서 가능한 행위는 수행할 수 있어야 한다.
* **I**: 의존 역전 원칙(DIP, Dependency Inversion Principle)
  * 의존 관계를 맺을 때 변화하기 쉬운 것 또는 자주 변화하는 것보다는 변화하기 어려운 것, 거의 변화가 없는 것에 의존하라는 것이다.
* **D**: 인터페이스 분리 원칙(ISP, Interface Segregation Principle)
  * 인터페이스를 클라이언트에 특화되도록 분리시키라는 설계 원칙이다.
> - [https://gmlwjd9405.github.io/2018/07/05/oop-solid.html](https://gmlwjd9405.github.io/2018/07/05/oop-solid.html)

#### 객체지향 프로그래밍과 절차지향 프로그래밍의 차이

#### java의 Static

#### java의 제네릭(Generic)

#### java의 가비지 컬렉션(Garbage Collection)

#### 객체(Object)란 무엇인가

#### 객체 직렬화(Serialization)와 역직렬화(Deserialization)란 무엇인가

#### 클래스와 인스턴스의 차이(Class vs Instance)

#### 오버로딩과 오버라이딩의 차이(Overloading vs Overriding)

#### Call by Reference와 Call by Value의 차이

#### 인터페이스와 추상 클래스의 차이(Interface vs Abstract Class)

#### 프로세스와 스레드의 차이(Process vs Thread)

<!-- ## 세션과 쿠키의 차이(Session vs Cookie) -->

<!-- ## 동기화 객체의 종류
* 뮤텍스와 세마포어의 차이 -->

<!-- ## 동기화와 비동기화의 차이(Syncronous vs Asyncronous) -->



## Main Reference Materials
> - [명품 Java Programming](https://www.booksr.co.kr/html/book/book.asp?seq=696811)
> - [inflearn 실전 자바 강좌](https://www.inflearn.com/course/%EC%8B%A4%EC%A0%84-%EC%9E%90%EB%B0%94-%EA%B0%95%EC%A2%8C/)

---
## :house: [Home](https://github.com/gmlwjd9405/java-and-springframework-interview-questions)
