---
title: 2주차 SSAFY Start Camp 챗봇 퀘스트
---
대전_3_얼렁뚱땅(10조), https://github.com/pch45/MiniGameHeaven



# I. 스펙(Specification)
## 구현된 어플리케이션의 주요 기능

### (1) 챗봇 기본 기능
- 사용자가 슬랙 채팅을 통해 전송한 텍스트 데이터를 분석한다.

### (2) 게임 목록 출력 기능
- 텍스트 데이터가 없을 경우 게임 목록을 출력한다.

### (3) 게임 실행  기능
- 텍스트 데이터가 게임 이름일 경우 게임을 시작한다.

### (4) 심리테스트 게임

- 심리 테스트 경우 바로 문제를 출력한다

- 사용자가 입력한 텍스트를 분석해 사용자의 심리를 출력한다.

### (5). 그외 게임들

- 게임이 시작되었다는 문구를 출력한다.

- 텍스트 데이터를 분석하여 게임 결과를 출력한다.

### (6) 유저 컨텍스트 분리

- 유저간 컨텍스트를 분리하여 모든 유저가 각자 게임을 할 수 있도록 한다.


<br>


# II. 회고(Retrospective)
## 어플리케이션 구현 과정에서의 어려움과 문제점
- 서버가 꺼져있을 때, request가 와 있을 경우 쌓여있던 response가 여러번 나와 어려움이 있었다.
- 사용자가 사용할 명령어를 정하는 것에 어려움이 있었다.
- 여러사람의 request를 각각 따로 처리하게 하는 것에 어려움이 있었다.


<br>

# III. 보완 계획(Feedback)
## 현재 미완성이지만 추가로 구현할 기능 및 기존 문제점 보완 계획

### (1) 자연어 처리 기능

- 챗봇에 입력 문을 입력하는 부분을 정해진 룰이 아닌 자연어 처리를 하여서 편한 대화 처럼 개발하고 싶다.

### (2) 추가 게임 구현

- 가로세로 낱말 퀴즈를 구현해서 추가하기

- 속담이어 맞추는 게임을 구현해서 추가하기
