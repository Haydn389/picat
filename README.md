## SW 사관학교 정글 나만의 무기 프로젝트 Picat

![Group 237](https://user-images.githubusercontent.com/69448918/215417167-6d308102-4bf7-4fda-84c1-fcedddd0e129.png)

얼굴 인식으로 쉽고 빠른 사진 공유 안드로이드 앱

수행기간 : 2022.12.22 ~ 2023.01.28 (5주)

참여인원 : Client 2명/ Server 2명

맡은역할
- 서비스 기획, 서버구축 및 API 설계
- 얼굴 인식 라이브러리 적용 및 처리 로직 개선
- 인물별 필터기능 구현
- 흐린 사진 작업서버 분리 및 DB관리

## 백엔드

### Skills

#### Javascript, Python

#### Node.js + Express, AWS Rekognition, S3, EC2, MongoDB Atlas, OpenCV

### 구현내용

- 서버 구축 및 배포

  - AWS EC2 Ubuntu 서버에 Node.js와 Express를 이용하여 서버 구축
  - RESTful API 명세서를 통해 프론트 엔드와 협업

- SaaS를 통한 메인 서버 부하 절감

  - AWS Rekognition를 이용한 얼굴 탐지 및 비교 기능
  - AWS S3 이용한 이미지 저장
  - MongoDB Atlas 서비스를 이용한 데이터베이스 구축

- 흐린 사진 판별 서버 (Node.js + Express)

  - OpenCV의 Laplacian 연산자를 이용하여 흐린 사진 판별 기능 구현

### 성능 개선

- 여러 얼굴인식 라이브러리 적용 및 테스트를 통한 얼굴 분류 작업 속도 개선

  - 사진 1장당 5초 → 1초

- 흐린 사진 판별 서버(서브 서버) 분리를 통해 timeout 해결 및 사용성 개선

## 발표 영상

https://youtu.be/M4QCKSfNTdQ

## 기능 구현 과정

<img src = "https://user-images.githubusercontent.com/59064298/215990999-f283ee1b-03f2-425d-a711-64d9d9cfd421.png" width="900px">

---

<img src = "https://user-images.githubusercontent.com/59064298/215989145-a2378339-7fbd-46bb-8993-2baa5ed19f2b.png" width="700px">

---

<img src = "https://user-images.githubusercontent.com/59064298/215989193-2c6c51af-18fc-405f-836e-b65ded349540.PNG" width="800px">

---

<img src = "https://user-images.githubusercontent.com/59064298/215991407-c2f28b55-567b-43b3-a5e2-d144036d45ae.png" width="600px">

---

<img src = "https://user-images.githubusercontent.com/59064298/215991463-16ad23b4-84e3-4256-9afd-6a6be44369c8.png" width="700px">

## 서비스 구조도

<img src = "https://user-images.githubusercontent.com/69448918/215393393-35f6f2c4-46c6-4a1c-9cb7-33732c45c531.png" width = "600px">

## 포스터

<img src = "https://user-images.githubusercontent.com/69448918/215391227-97fd1220-f07f-4861-beff-656e605f8699.png">
