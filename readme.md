This is an H2
-------------

* 1단계
  - 2단계
    + 3단계
      + 4단계

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

2장 의미 있는 이름
=============

## 2-1. 의도를 분명히 밝혀라
* 변수,함수 클래스이름에 의도를 분명히 드러낼수 있도록 지어야 한다


```java
//의미없는 이름의 코드
public List<int[]> getThem() {
  List<int[]> list1 = new ArrayList<>();
  for (int[] x : theList)
    if (x[0] == 4)
        list1.add(x);

  return list1;
}
```

```java
//의미있는 이름의 코드
public List<int[]> getFlaggedCells() {
  List<Cell> flaggedCells = new ArrayList<>();
  for (Cell cell : gameBoard)
    if (cell.isFlagged())
        flaggedCells.add(cell);

  return flaggedCells;
}
```

## 2-2. 그릇된 정보를 피하라

## 2-3. 의미 있게 구분하라




