---
layout: single
title: "JAVA - Basic"
categories: Back-End
tag: [JAVA]
toc: true
author_profile: false
typora-root-url: ../
sidebar:
  nav: "counts"
redirect_from:
  - /coding/day01
# search: false
---

![Java-Logo](/images/2023-06-07-java_basic/Java-Logo.png){: .img-width-half .align-center }

![Eclipse-Logo](/images/2023-06-07-java_basic/Eclipse-Logo.png){: .img-width-half .align-center }

## Ex01_HelloJava

{% highlight ruby %}
package day01_basic; // 패키지를 명시

public class Ex01_HelloJava { // 클래스명 : 소스파일명과 같다.
public static void main(String[] args) { // main 함수 (x) -> main 메소드(o)

    // 주석 : C와 같은 방법으로 처리 (//, /\* \*/)
    // 이클립스 주석 자동 완성 : Ctrl + /
    
    // 실행 : Ctrl + F11
    
    System.out.println("Hello Java World"); // print line : 줄바꿈 진행
    System.out.print("Hello Java World");
    
    // 자동완성 기능 : Ctrl + Space
    System.out.println("Hello World");

}
}
{% endhighlight %}

## Ex02_Literal

{% highlight ruby %}
package day01_basic;

public class Ex02_literal {
public static void main(String[] args) {

    // 1. 문자 표현 방식 (홑따옴표, 작은 따옴표)
    // 한글과 영문에 모두 적용된다.
    System.out.println('A');
    System.out.println('한'); // C는 안 되고, java는 된다.
    
    // 2. 문자열 표현 방식 (쌍따옴표, 큰따옴표)
    System.out.println("Hello");
    
    // 3. 정수나 실수 표현 방식 (그냥 입력)
    System.out.println(100);
    System.out.println(3.141592);
    
    // 4. 논리값 표현 방식
    System.out.println(true);
    System.out.println(false);

}
}
{% endhighlight %}
