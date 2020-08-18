---
title: "[Java] next()와 nextLine()"
tags:
- Java
- String
categories:
- Java
excerpt: Java에서 String 입력 시 next()와 nextLine()의 차이
---

String 클래스에 Scanner를 사용해 입력할 때  
next()와 nextLine()의 차이에 대해 알아보자.
## next()
* 코드

```java
Scanner scan - new Scanner(System.in);
String s;
s = scan.next();

System.out.println(s);
```
* "Hello java" 입력시 출력

```
Hello
```

* __next() : 문자 or 문자열을 공백 기준으로 입력 받는다.__  

## nextLine()

* 코드

```java
Scanner scan - new Scanner(System.in);
String s;
s = scan.nextLine();

System.out.println(s);
```

* "Hello java" 입력시 출력

```
Hello java
```

* __nextLine() : 문자 or 문자열 라인 전체를 입력 받는다.__
