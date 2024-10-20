# java-calculator-precourse

1. 프로그램 실행 시 "덧셈할 문자열을 입력해 주세요." 출력
2. 문자열 입력 받기
3. 쉼표(,) 또는 콜론(:)을 기준으로 분리
4. 분리한 숫자 합산
    1. 예: "" => 0, "1,2" => 3, "1,2,3" => 6, "1,2:3" => 6
5. "\\\\" 와 "\n" 사이에 위치하는 문자 커스텀 구분자 사용
    1. 예를 들어 "//;\n1;2;3"과 같이 값을 입력할 경우 커스텀 구분자는 세미콜론(;)이며, 결과 값은 6이 반환되어야 한다.
6. 잘못된 입력의 경우 `IllegalArgumentException` 발생시킨 후 애플리케이션 종료
7. 결과 출력

```
ex) 결과 : 6
```

8. 최종 예시

```
덧셈할 문자열을 입력해 주세요.
1,2:3
결과 : 6
```