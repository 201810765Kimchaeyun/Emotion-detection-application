# 감정공유 익명채팅 어플리케이션 '공감이'

## 프로젝트 소개 
* Microsoft에서 제공하는 emotion-recognition API를 사용하여 얼굴인식과 감정인식을 하였으며 채팅 기능(회원가입, 로그인, 채팅방 개설)을 구현하는데 필요한 DB는 Firebase로 구축하였음.  
* 표정으로 자연스럽게 드러나는 감정을 측정하여 감정을 판단하고(기쁨, 슬픔, 화남, 두려움 중), 자신과 같은 감정을 지닌 사람들과 익명 채팅을 통해 공감 혹은 위로를 받을 수 있음.

## 개발기간
* 2019/10 ~ 2019/12 (2개월)

## 팀원
* 김채윤, 이현서, 유세빈

## 개발 환경
* 개발 툴 : Android Studio
* 데이터베이스 : Firebase
* 개발 언어: JAVA
* API : MicroSoft에서 제공하는 emotion-recognition 사용. 이를 사용하기 위해서 azure 구독 키 발급.

https://docs.microsoft.com/ko-kr/xamarin/xamarin-forms/data-cloud/azure-cognitive-services/emotion-recognition


## 개발 내용
### 1. 회원가입과 로그인
<p>
 <img src="https://user-images.githubusercontent.com/60181129/99414946-ad768600-293a-11eb-9d3e-c8352817a74d.jpg"  width="30%" height="10%"/>
 <img src="https://user-images.githubusercontent.com/60181129/99414978-b36c6700-293a-11eb-9b70-e0b7264985ab.jpg"  width="30%" height="10%"/>
 <img src="https://user-images.githubusercontent.com/60181129/99414955-aea7b300-293a-11eb-8443-d9db3442dad3.jpg"  width="30%" height="10%"/>
</p>

### 2. 사진 촬영
* 카메라 사용 권한 동의 및 카메라 연동

<p>
 <img src="https://user-images.githubusercontent.com/60181129/99414959-b0717680-293a-11eb-9214-86dfaf9ee61e.jpg"  width="30%" height="20%"/>
 <img src="https://user-images.githubusercontent.com/60181129/99414964-b0717680-293a-11eb-80e4-9da0119b7056.jpg"  width="30%" height="20%"/>
 <img src="https://user-images.githubusercontent.com/60181129/99414965-b10a0d00-293a-11eb-9ae6-e4034b6e0bed.jpg"  width="30%" height="20%"/>
</p>

### 3. 감정인식 및 감정 선택
* 촬영된 얼굴 사진의 감정인식 후 4개의 감정(기쁨, 슬픔, 화남, 두려움) 중 상위 2개 감정 출력 후 감정 선택

### 4. 채팅방 선택 or 개설 후 채팅
* 채팅방을 개설하여 익명의 사람들과 채팅을 통한 감정을 공유

 
## 현재
* azure 체험판 구독키 기간 만료로 새로운 구독 키 발급 필요
<img src=""  width="30%" height="30%"/>
