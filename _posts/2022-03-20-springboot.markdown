---
layout: post
title: springboot
date: 2020-01-02 19:20:23 +0900
category: springboot
---

# springboot란?

### springboot는 조금 복잡하고 무거운 프레임워크를 쉽게 이용하기 위해 만든 툴이다.
#### -스프링 프레임워크와 서드파티 라이브러리가 내장되어 있어 간단한 설정으로 프로젝트를 시작할 수 있다.
#### -내장된 컨테이너에 톰캣(tomcat)이 배치되어 있어 개발한 웹어플리케이션을 단독으로 실행할 수 있습니다.

# intellij 무료 버전인 Community 버전에서 springboot 시작하기

### 스프링 이니셜라이즈 접속하기 
[이니셜라이즈](https://start.spring.io/)

### - project
#### 

### - language
#### 

### spring boot
#### 

## project metadata

### group -> com.example
### artifact -> demo
### name -> demo
### description -> demo project for spring boot
### package name -> com.example.demo

### packaging
#### jar 선택시 tomcat 자동 배치되어 단독 실행 가능

### java
#### 자바 버전 선택

# Dependencies 의존성 라이브러리 설정
### 오른쪽 상단의 add dependencies… 선택
### 빈칸에 web 검색
### spring web 선택

# PROJECT 생성하기

### 하단에 GENERATE를 클릭
#### -> demo.zip이 다운로드 됨

### 원하는 파일 위치에 압축 풀기

# intellij IDEA에서 PROJECT 열기

### intellij에서 'Open' 클릭

### demo 위치를 찾아 선택

# 실행 확인
### 아무것도 하지 않고  src>main>java>com.example.demo>DemoApplication에서 'public class DemoApplication {' 옆의 실행 버튼 눌러 실행
#### 잠시 기다린다.(몇 분 정도 소요)

### 하단 실행 로그에서 port 번호 확인

# 크롬에서 접속하기
### http://localhost:8080을 주소창에 입력
#### 404 에러가 정상적으로 발생 ( 아직 아무런 입력도 하지 않았으므로 당연한 결과다.)


