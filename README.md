# 📚 도담도담  
다문화 가정 학생과 부모를 위한 AI 한국어 교육 지원 및 발음 향상 어플리케이션

## 📄Table of contents
0. [폴더 구조]()
1. [프로젝트 진행기간](https://github.com/yyeongha/Dodam-Dodam#-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%A7%84%ED%96%89%EA%B8%B0%EA%B0%84-)
2. [배경](https://github.com/yyeongha/Dodam-Dodam#%EF%B8%8F-%EB%B0%B0%EA%B2%BD)
3. [개요](https://github.com/yyeongha/Dodam-Dodam?tab=readme-ov-file#%EF%B8%8F-%EA%B0%9C%EC%9A%94)
4. [주요기능](https://github.com/yyeongha/Dodam-Dodam?tab=readme-ov-file#%EF%B8%8F-%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5)
5. [개발환경](https://github.com/yyeongha/Dodam-Dodam?tab=readme-ov-file#%EF%B8%8F-%EA%B0%9C%EB%B0%9C%ED%99%98%EA%B2%BD)
6. [ERD](https://github.com/yyeongha/Dodam-Dodam?tab=readme-ov-file#-erd)

## 📂 폴더 구조


## 🏃 프로젝트 진행기간 🏃
2024.04.08 ~ 2024.04.28

## ☀️ 배경
경기도 내 다문화 가정의 학생 수가 계속 증가하고 있는 가운데, 이들의 한국어 교육 지원은 점점 더 중요한 과제로 부각되고 있다. 많은 다문화가정 학생들이 한국어 능력 부족으로 학교 생활에 적응하는 데 어려움을 겪고 있으며, 이로 인해 일반 가정의 학생들보다 중도 이탈률이 4배 이상 높은 상태이다. 

![다문화가정수](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/%EB%8B%A4%EB%AC%B8%ED%99%94%EA%B0%80%EC%A0%95%EC%88%98.png?raw=true)

또한 다문화 가정의 학생들이 한국어를 배우는 데 있어 부모의 한국어 능력도 중요한 요소이나 결혼 이민자들의 한국어 능력이 유창하지 않은 경우가 많아, 이는 자녀와의 의사소통뿐만 아니라 자녀의 언어 발달에도 부정적인 영향을 미치고 있다.

![다문화부모어려움](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/%EB%8B%A4%EB%AC%B8%ED%99%94%EB%B6%80%EB%AA%A8%EC%96%B4%EB%A0%A4%EC%9B%80.png?raw=true)

즉, 이러한 상황을 개선하기 위해 다문화 가정의 학생뿐만 아니라 부모를 위한 한국어 교육 서비스가 제공되어야 함을 시사한다. 


## ☀️ 개요
경기도 내 다문화 가정 학생 수가 계속 증가함에 따라 이들의 한국어 교육은 점점 중요한 과제로 부각되고 있다.  

‘도담도담’은 생성형 AI를 통해 실생활 대화 체험 기능과 발음 분석 및 리포트 작성 기능을 제공함으로써 부모와 학생이 같이 공부할 수 있게 도와주는 AI 한국어 교육 지원 어플리케이션이다. 

해당 서비스를 통해 경기도 내의 다문화가정 교육관련 예산 절감과 다문화 가정의 한국어 능력 향상을 기대할 수 있다.


## ☀️ 주요기능
### * 부모와 함께하는 서비스
![1. 부모와 함께하는 서비스](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/1.%20%EB%B6%80%EB%AA%A8%EC%99%80%20%ED%95%A8%EA%BB%98%ED%95%98%EB%8A%94%20%EC%84%9C%EB%B9%84%EC%8A%A4.png?raw=true)

해당 서비스는 양육자와 자녀가 함께 이용하며 학습하는 것을 중심으로 기획되었다. 

메인 화면에서는 부모님과 함께한 학습의 연속된 날짜를 보여주어, 매일매일의 공부를 놓치지 않고 꾸준히 진행할 수 있는 동기부여가 되도록 했고, 일상에서의 책 읽기나 말하기와 같은 다양한 미션을 통해, 자녀가 스스로 학습에 능동적으로 참여하고 자신감을 가질 수 있도록 설계되었다.


### * 녹음 및 리포트 제공 서비스
![2. 녹음 및 리포트 제공 서비스](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/2.%20%EB%85%B9%EC%9D%8C%20%EB%B0%8F%20%EB%A6%AC%ED%8F%AC%ED%8A%B8%20%EC%A0%9C%EA%B3%B5%20%EC%84%9C%EB%B9%84%EC%8A%A4.png?raw=true)

양육자와 자녀는 자신들이 선호하는 책을 선택해 번갈아 가며 읽고, 읽기 완료 후에는 발음에 대한 자세한 리포트를 받을 수 있다. 해당 리포트는 생성형AI 모델인 XAI을 활용해 각 사용자의 발음을 평가하고, 개선이 필요한 부분을 집어내어 특정 문장들을 복습할 수 있도록 안내한다. 

해당 기능을 통해 사용자는 독립적으로 발음을 연습하고 교정할 수 있기 때문에, 방문 교육지도사 없이도 효과적인 교육이 가능하므로 다문화 자녀 교육 지원에 사용되는 예산을 절감할 수 있고, 다문화 가정에서는 경제적 부담을 줄일 수 있다.


### * 챗봇 기반의 상황극 기능
![3. 챗봇 기반의 상황극 기능](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/3.%20%EC%B1%97%EB%B4%87%20%EA%B8%B0%EB%B0%98%EC%9D%98%20%EC%83%81%ED%99%A9%EA%B7%B9%20%EA%B8%B0%EB%8A%A5.png?raw=true)

해당 서비스에서는 사용자가 몰입하고 싶은 다양한 상황 중 하나를 선택하여 실제로 경험할 수 있다. 선택한 시나리오에 맞춰 생성형 AI가 상황에 알맞은 대화를 제공하고, 사용자의 답변이 문맥에 맞는지 분석해준다. 

또한 TTS와 STT 기술을 활용함으로써, 사용자는 마치 실제 상황에 있는 것처럼 자연스러운 대화를 경험할 수 있게 도와준다.

## 🖥️ 개발환경
### 🖱 환경
* CPU : Intel(R) Core(TM) i5-8265U
* GPU : NVIDIA GeForce RTX 3060 
* CUDA version : 11.8
* PyTorch version : 2.3.0

### 🖱 데이터
|서비스|데이터설명|출처|주소|
|:---:|:---:|:---:|:---:|
|녹음 및 리포트 제공 서비스&nbsp;&nbsp;&nbsp;|한국전래동화|국립어린이 청소년도서관 다국어동화구연|https://www.culture.go.kr/data/openapi/openapiView.do?id=391&keyword=%EB%8B%A4%EA%B5%AD%EC%96%B4%EB%8F%99%ED%99%94%EA%B5%AC%EC%97%B0_%ED%95%9C%EA%B5%AD%EC%A0%84%EB%9E%98%EB%8F%99%ED%99%94&searchField=all&gubun=A|
|챗봇 기반의 상황극 기능|한국어 대화|AI Hub|https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=116|
|챗봇 기반의 상황극 기능|주제별 텍스트 일생 대화 데이터|AI Hub|https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=543|


### 🖱 기술 스택

|분야|사용기술|
|:---:|:---:|
|OS|Ubuntu22.04|
|IDE|VSCode, Colab|
|CI/CD|docker|
|Design|Figma|
|Tool|Notions|


## 📈 ERD
![ERD](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/erd.png?raw=true)

총 3개의 TABLE로 구성되어있으며 각각의 TABLE의 역할은
다음과 같다.

1. User: 유저에 대한 정보를 저장
2. User_Feedback: 유저의 발음 중 부정확한 부분과 해당 부분의 음성을 저장
3. Book: 책 정보에 대한 데이터 저장


