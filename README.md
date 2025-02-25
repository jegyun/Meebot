# MeeBot - AI 사회자 서비스

### 📜 목차
 1. [소개](#-소개)
 2. [서비스 화면](#-서비스-화면)
 3. [주요 기능](#-주요-기능)
 4. [개발 환경](#%EF%B8%8F-개발-환경)
 5. [시스템 아키텍처](#-시스템-아키텍처)
 6. [Conventions](#-conventions)
 7. [구성원](#-구성원)
---

## 🤍 소개
<b>AI 사회자가 진행하는 화상 회의 서비스</b>

## 🖼️ 서비스 화면
### 온보딩
### 닉네임, 마이크 및 카메라 설정
### 발표 순서 설정
### 발표 내용 요약
### 질의 응답
### 최종 요약 저장

## ✨ 주요 기능
- `AI 사회자`
    - AI 미유가 발표회의 시작부터 종료까지 진행
- `실시간 스크립트`
    - 발표 내용 실시간 스크립트 제공
- `요약 및 추천 질문`
    - 발표자가 발표 종료 시, 해당 발표에 대한 요약과 추천 질문 제공
- `요약본`
    - 발표회 종료 후, 모든 발표자에 대한 발표 및 질의 응답 내용이 로그인 된 참여자의 보관함에 저장.
    - 요약본은 Notion 페이지에  추가하거나 PDF로 다운로드 가능

## 🖥️ 개발 환경
| **분야**           | **기술**          |
|------------------|------------------|
| **프로그래밍 언어** | TypeScript, Java |
| **프레임워크**     | FE: React, Redux <br> BE: Spring, Spring Boot |
| **데이터베이스**   | MySQL            |
| **버전 관리**     | Git              |
| **클라우드**      | AWS              |
| **배포 도구**     | Docker, Jenkins  |
| **테스트 프레임워크** | Jest          |
| **API**          | RESTful API      |

## 시스템 아키텍처
![Image](https://github.com/user-attachments/assets/ee7f0c11-11c8-4765-9816-92dd5b796b04)


## ERD
![Image](https://github.com/user-attachments/assets/d8bb1431-b577-4317-ae46-7ca9f8ba42ce)

      
## 🙋🏻🙋🏻‍♀️ 구성원


| 김선주 | 김민재 | 배지해 | 이송희 | 제동균 | 하시윤 |
|:---:|:---:|:---:|:---:|:---:|:---:|
|![Image](https://github.com/user-attachments/assets/113394aa-f875-49cb-8257-180a39a36df3)|![Image](https://github.com/user-attachments/assets/96f08f41-2d76-4143-bdf6-de8acefab6ae)|![Image](https://github.com/user-attachments/assets/4546914a-61f0-4da7-89ef-d537268d7a88)|![Image](https://github.com/user-attachments/assets/31299ec3-23c8-4ddb-ba70-10c0025d7e67)|![Image](https://github.com/user-attachments/assets/bcfa611c-d802-4bb6-9041-924a793a74fd)|![Image](https://github.com/user-attachments/assets/2ca06b89-5d46-4d48-8029-129cd7d9c825)|

### 팀원 역할

- **김선주 (BE 팀장)**
    - 서비스 API 구현
    - CI/CD
    - OpenVidu
    - Notion / PDF 다운로드
- **김민재**
    - 서비스 API 구현
    - ChatGPT
    - DB
- **배지해**
    - UI/UX 디자인 총괄
    - Oauth2 로그인
    - UI 페이지 구현
- **이송희**
    - UI/UX 디자인
    - OpenVidu 구현
    - STT 스크립트 개발
- **제동균 (FE 팀장)**
    - UI/UX 구현
    - OpenVidu 구현
    - TTS
- **하시윤**
    - 서비스 API 구현
    - Oauth2 로그인
    - OpenVidu(채팅)
    - STT Q&A 개발
