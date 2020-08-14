---
title: Table of Contents 연습하기
toc: true
toc_sticky: true
toc_label: 페이지 주요 목차
tags:
- Github_Pages
- TOC
- Test
categories:
- Github_Pages
- TOC
- Test
---

Table of Contents 사용법 연습하기

TOC는 H1~H6의 헤더 목록을 표시하는 기능

minimal-mistakes에서는 TOC를 오른쪽 사이드바에 표시

```
toc: true
```
TOC 사용시 포스트에 위와 같이 toc를 설정  
로컬 admin 사용시 하단 필드에 작성

```
toc_sticky: true
```
sticky는 사이드바에 고정하는 역할  
화면을 스크롤해도 toc는 고정되어있다.

```
toc_label: "페이지 주요 목차"
```
label은 toc의 제목을 설정    
디폴트는 "On this page"이다.

# TOC H1
## TOC H2
### TOC H3
#### TOC H4
##### TOC H5
###### TOC H6 - 1
###### TOC H6 - 2
###### TOC H6 - 3
