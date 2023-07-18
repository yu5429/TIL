**중첩 반복문에서 조건을 충족시 바깥쪽 반복문까지 한 번에 탈출이 필요할 때 사용한다.**<br><br>
사용예시<br>
```
outerLoop: // 라벨 지정
for (int i = 0; i < 5; i++) {
    for (int j = 0; j < 3; j++) {
        if (someCondition) {
            break outerLoop; // 바깥쪽 반복문까지 탈출
        }
    }
}
```
