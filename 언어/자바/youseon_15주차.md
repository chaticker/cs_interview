## 자바 컴파일 과정을 설명하세요.

답변: 컴파일러가 소스코드를 자바 바이트코드로(.class) 변환한다, JVM(자바가상머신)이 그 바이트코드를 기계어로 변환하여 인터프리터 방식으로 어플리케이션을 실행한다.

전처리 : #define, #include 지시자 해석
컴파일 : 고급 언어 소스 프로그램 입력받아 어셈블리 파일을 만듦
어셈블 : 어셈블리 파일을 오브젝트 파일로 만듦
링크 : 오브젝트 파일을 엮어 실행파일을 만들고 라이브러리 함수 연결
실행