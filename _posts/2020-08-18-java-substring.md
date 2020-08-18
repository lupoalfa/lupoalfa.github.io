---
title: "[Java] Substring 함수로 문자열 슬라이싱"
tags:
- Java
- String
- Substring
- 문자열자르기
- Function
- 함수
categories:
- Java
excerpt: Substring 함수를 이용하여 문자열을 슬라이싱 해보자.
toc: true
toc_sticky: true
toc_label: Substring 함수
---

# Substring
SubString 함수를 사용해 문자열 슬라이싱을 해보자  
## String 구조 파악하기

먼저 String 구조를 알아야 SubString 함수를 이용할 수 있다.

| String | A |  B | C | D | E |
|:----:|:----:|:----:|:----:|:----:|:----:|
| index | 0 | 1 | 2 | 3 | 4 |

__String 클래스는 위와 같이 char로 이루어진 배열로 생각하는 것이 편하다.__

## Substring 함수
Substring 함수는 String의 index를 매개변수로 받으며, 매개변수의 개수에 따라 기능이 달라진다.

* 매개변수 1개 : 주어진 index부터 끝까지 포함하여 자르기
* 매개변수 2개 :  첫번째 매개변수로 주어진 index 부터 두번째 주어진 index __전__ 까지 포함하여 자르기

```java
STRING.substring(start); // start위치 부터 끝까지 포함하여 자르기
STRING.substring(start,end); // start위치 부터 end위치 바로 전까지 포함하여 자르기

// ex)
String str = "ABCDE";

str.substring(2);
// 결과 : CDE
str.substring(1,4);
// 결과 : BCD
```
