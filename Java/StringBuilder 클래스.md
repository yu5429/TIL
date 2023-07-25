**StringBuilder는 Java에서 문자열을 동적으로 조작하기 위한 클래스**<br>

사용예시<br>
```
StringBuilder sb = new StringBuilder();

// 문자열 추가
sb.append("Hello");
sb.append(" World!");

// 문자열 삽입
sb.insert(5, "Awesome ");

// 문자열 삭제
sb.delete(0, 6);

// 문자열 변경
sb.replace(6, 11, "Java");

// 문자열 검색
int index = sb.indexOf("Java");

// 문자열 길이
int length = sb.length();

// 문자열 출력
System.out.println(sb.toString()); // 출력 결과: "Awesome Java!"

System.out.println("Index of 'Java': " + index); // 출력 결과: "Index of 'Java': 8"

System.out.println("Length: " + length); // 출력 결과: "Length: 13"
```
