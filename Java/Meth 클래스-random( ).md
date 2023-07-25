**random() 메소드는 0.0 이상 1.0 미만의 범위에서 임의의 double형 값을 하나 생성하여 반환. **<br>
0~99까지의 난수 생성 예시
```
System.out.println((int)(Math.random() * 100)); // 0 ~ 99

 

Random ran = new Random();

System.out.println(ran.nextInt(100));           // 0 ~ 99
```
자바에서는 Math 클래스의 random() 메소드뿐만 아니라 java.util 패키지에 포함된 Random 클래스의 nextInt() 메소드를 사용해도 난수를 생성가능 <br>
만약 특정 범위에 속하는 난수를 생성하려면, 다음과 같이 난수 생성 범위를 조절 가능.
```
(int)(Math.random() * 6);       // 0 ~ 5

((int)(Math.random() * 6) + 1); // 1 ~ 6

((int)(Math.random() * 6) + 3); // 3 ~ 8
```
