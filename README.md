# 💗 ForShop
![MockUp4](https://github.com/j2an777/ForShopPlus/assets/110087099/9d012c4e-e5ec-48e9-b00e-709b3995a205)

**프로젝트 기간** : 2023.09.11 ~ 2023. 12. 14

🔗 [웹 시연영상 보러가기](http://img.youtube.com/vi/L26RSg6RzxA/0.jpg)
<br/>
<br/>

## ✨ 프로젝트 소개

### 누구나 언제나 어디서나 최고의 순간을 담아내다 For Shop

- For Shop은 **AI 카메라 어플기반 SNS 서비스**입니다.
- 촬영 단계에서 구도 잡는 과정을 포커싱으로 실시간으로 사람의 비율을 수치로 제공합니다.
- 웹, 앱에서 연동으로 사진 업로드 및 공유가 가능합니다.
- 웹에서는 릴스, 숏츠를 벤치마킹하여 2개의 영상을 놓고 동작 비교 분석을 제공합니다.
<br/>

## 🔨 서비스 아키텍처
![image](https://github.com/user-attachments/assets/6e5ca682-48dd-4f59-8561-a431b9f99b2f)
<br/>

## ⭐️ 주요 기능

### 📱 모바일
- ObjectDetection과 PoseEstimation을 이용하여 사람을 1 기준으로 비율을 수치로 제공합니다.

![KakaoTalk_20240723_114047878](https://github.com/user-attachments/assets/70fc0c60-6be9-401b-95b4-c66dcb6f2191)
![image](https://github.com/user-attachments/assets/a48a19db-e263-4226-8763-281b243b47ac)

#### 📌 메인 (카메라)
- 카메라 화면에 격자선 기능 제공
- 후면 카메라 기능 제공
- 마이 갤러리에 넘어갈 수 있게 버튼 제공

![image](https://github.com/user-attachments/assets/ef357448-556a-44fd-aeeb-9021072e8a3a)

#### 📌 실시간 비율 제공
- 토글 버튼 클릭시 ObjectDetection과 YoloV4 모델의 Pose Estimation을 활용하여 인물의 피사체를 1을 기준으로 비율을 제공합니다.

![image](https://github.com/user-attachments/assets/f4338978-d148-4375-b88f-4ca85cbeb1f0)

#### 📌 게시물 SNS 
- 이미지와 닉네임 조회
- 좋아요 기능 가능

![image](https://github.com/user-attachments/assets/91f641a9-303b-4d45-a840-e0022ce749f5)

### 💻 웹

#### 📌 인트로 페이지
- 데모 버전 영상을 통해 어떤 서비스인지 알게끔 표현
- ThreeJS 스크롤 애니메이션을 넣어 동적으로 서비스 소개 디자인

![image](https://github.com/user-attachments/assets/c10ff85d-5011-4b2e-ae78-bfd484372ddf)

![image](https://github.com/user-attachments/assets/8190ef9b-6b5a-427e-a061-54b643930f18)

#### 📌 메인 페이지
- 이미지와 비디오 게시물 조회
- 검색으로 게시물 찾기 가능
- 페이징 처리로 8개 이미지 씩 렌더링 하도록 설계

![image](https://github.com/user-attachments/assets/738c7b2a-b31a-43e3-b6c9-64cd4e75845d)

#### 📌 이미지 상세조회
- 댓글 기능
- 이미지에 대한 제목과 설명, 해시태그 조회 가능

![image](https://github.com/user-attachments/assets/33e4e631-c30e-4b69-8c09-542ee150c328)

#### 📌 로그인 & 회원가입
- 닉네임, 이메일, 비밀번호로 회원가입
- 비밀번호 확인으로 1차 검증
- 로그인은 이메일, 비밀번호로 구성

![image](https://github.com/user-attachments/assets/169a7a4a-b3e9-45dc-a3c7-d65929aedc06)

#### 📌 이미지 & 비디오 업로드
- 이미지, 제목, 해시태그, 설명으로 구성

![image](https://github.com/user-attachments/assets/b4eff1dc-56b4-40f5-8d63-570c69ae9fdd)

#### 📌 마이 페이지
- 자신의 계정에 대한 게시물 조회
- 특정 게시물 삭제 가능

![image](https://github.com/user-attachments/assets/7d89889c-c718-4458-b343-88f6a2f2108c)

#### 📌 영상 비교 분석
- 2개의 영상을 업로드

![image](https://github.com/user-attachments/assets/ddb449b8-8bb5-41c4-9c43-aa78942b36cd)
- 영상 분석 중을 애니메이션으로 표현

![image](https://github.com/user-attachments/assets/83beedfe-6ddb-443e-a63a-e6d9ed486a48)
- 비교 분석 결과 페이지

![image](https://github.com/user-attachments/assets/d614d6ec-69f7-44e4-a14f-5c65a24c7f25)

![image](https://github.com/user-attachments/assets/22a189ef-2b5e-4e13-bb09-da45ce685b25)
