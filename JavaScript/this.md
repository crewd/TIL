# this

`this`는 자신이 속한 객체 또는 자신이 생성할 인스턴스를 가리키는 자기 참조 변수이다.

`this`는 메서드에서 객체에 저장된 정보에 접근하기 위해 사용된다.

`this`는 어떻게 호출되었는지에 따라 값이 결정된다.

- 전역 공간: window
- 함수 내부: window
- 메서드: 해당 메서드를 호출한 객체
- 생성자: 생성자 함수가 생성할 인스턴스
- 이벤트 리스너: 이벤트를 발생시킨 객체