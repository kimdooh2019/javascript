DataType
=============


## 데이터 타입의 분류
- 자바스크립트(ES6)는 7개의 데이터 타입을 제공한다. 
- 7개의 데이터 타입은 원시 타입(primitive type)과 객체 타입(object/reference type)으로 분류할 수 있다.

원시 타입(primitive type)
- 숫자(number) 타입: 숫자 (정수, 실수)
- 문자열(string) 타입: 문자열
- 불리언(boolean) 타입: 논리적 참(true)과 거짓(false)
- undefined 타입: 선언은 되었지만 값을 할당하지 않은 변수에 암묵적으로 할당되는 값
- null 타입: 값이 없다는 것을 의도적으로 명시할 때 사용하는 값
- Symbol 타입: ES6에서 새롭게 추가된 7번째 타입
- 객체 타입 (object/reference type): 객체, 함수, 배열 등


>선언(Declaration)과 정의(Definition)
undefined를 직역하면 “정의되지 않은”이다. 일반적으로 정의란 개념은 어떤 대상을 명확하게 규정하는 것을 의미한다. 자바스크립트의 undefined에서 말하는 정의란 변수에 값을 할당하여 변수의 실체를 명확히 하는 것을 말한다.
다른 프로그래밍 언어에서는 선언과 정의를 엄격하게 구분하여 사용하는 경우가 있다. 예를 들어 C에서 선언과 정의는 “실제로 메모리 주소를 할당하는가”로 구분한다. 단순히 컴파일러에게 식별자의 존재 만을 알리는 것은 선언이고 실제로 컴파일러에게 변수를 생성하도록 하여 식별자와 메모리 주소가 연결되면 정의로 구분한다.
자바스크립트의 경우, 변수를 선언하면 정의가 이루어지기 때문에 선언과 정의의 구분이 모호하다. 자바스크립트에서 선언은 식별자가 생성되었지만 값이 아직 할당되지 않은 상태를 말한다. 자바스크립트에서 정의는 식별자가 생성되었고 값까지 할당되어 있는 상태를 의미한다.


