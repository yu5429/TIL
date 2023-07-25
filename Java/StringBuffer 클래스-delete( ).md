**'StringBuffer클래스의 'delete()'메소드는 문자열을 수정하는 데 사용되는 메소드이다. **<br>
사용예시
```
public class StringBufferExample {
    public static void main(String[] args) {
        StringBuffer stringBuffer = new StringBuffer("Hello, World!"); //인스턴스 생
        System.out.println(stringBuffer);               //출력 결과 'Hello, World!'

        stringBuffer.delete(0, 6);                      // 문자열의 인덱스 0부터 5까지 삭제
        System.out.println(stringBuffer);               //출력 결과 'World!'
    }
}
```
