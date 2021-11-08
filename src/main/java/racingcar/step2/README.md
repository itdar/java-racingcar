# **step.2 문자열계산기**

### **요구사항**
1. 입력한 문자열 값 -> 사직연산 수행
2. "2 + 3" -> 입력한 문자 사의 빈공백
3. 나눗셈의 경우 정수로 떨어지는 값만 취급
4. 입력값 순서에 따라 사칙연산 수행

### **TODO List**
1. 문자열 자른 후 스트링 배열반환
2. 수행할 연산 메서드 구현
3. 작은 단위로 테스트
4. 큰 단위로 테스트 -> stack 만들고 값 넣기
5. 검증 코드 구현 
    - 정수 나누기 체크
    - 빈값 or null 체크
    - 사칙연산 기호 체크
6. util 클래스 사용하여 메서드 분리    
7. 인터페이스 분리, 중복 코드 추상화    