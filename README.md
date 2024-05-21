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

#### 1. 음성인식
사용자가 말하는 음성을 녹음하고, 이 녹음된 음성을 텍스트로 변환하는 과정에서 'KoSpeech' 모델을 사용한다. KoSpeech는 한국어 전문 자동 음성 인식(ASR)을 위한 오픈 소스 툴킷으로, PyTorch 기반으로 작동한다. 이 툴킷은 deep speech 2, Listen, Attend and Spell (LAS), Transformer, Joint CTC-Attention LAS 등 다양한 딥러닝 모델을 지원하며, 특성 추출을 위한 다양한 옵션을 제공한다. 또한 모델의 구조와 특성을 자유롭게 선택할 수 있어, 한국어 음성 인식을 더욱 효율적으로 수행할 수 있다. KoSpeech는 한국어 음성 데이터셋 중 가장 큰 규모인 KsponSpeech를 학습할 수 있도록 지원하며, 음성인식 기능에서는 이 데이터셋을 활용하여 KoSpeech 툴킷을 훈련시켰다. 

[kospeech](https://github.com/sooftware/kospeech?tab=readme-ov-file)

#### 2. 발음 분석
변환된 텍스트를 분석하여 사용자의 발음이 얼마나 정확한지 평가한다. 이는 'SpeechFeedback'라는 알고리즘을 통해 진행한다. 

‘SpeechFeedback’은 Python을 기반으로 하는 응용 프로그램으로, 사용자로부터 오디오 녹음을 요청하며, 녹음된 오디오는 sounddevice와 scipy.io.wavfile 라이브러리를 사용하여 PCM 파일로 저장된다. 

‘SpeechFeedback’에서 이 파일은 로컬에서 운영 중인 FastAPI 서버로 전송되어 사용자의 발음과 표준 IPA를 비교 분석한다. 하지만, 아동을 대상으로 하는 서비스의 특성상, IPA 대신 한국어로 표기한 발음과 비교분석하는 것으로 대체하였다. 

[SpeechFeedback](https://github.com/DevTae/SpeechFeedback?tab=readme-ov-file)

#### 3. 피드백 생성
발음이 정확하지 않은 부분에 대해, 어떻게 발음을 개선할 수 있는지를 알려준다. 이 정보는 표준 한국어 데이터 파일(csv 파일)에 기록되어 있으며, 시스템은 이 파일을 읽고 사용자에게 발음을 개선할 수 있는 구체적인 조언을 제공한다. 

이 과정을 통해 발음 피드백이 JSON 형식으로 출력되며, 이 피드백을 바탕으로 사용자의 발음이 정확할 경우 프로그램은 종료되고, 발음에 오류가 있을 경우 필요한 교정 사항(before)과 권장 발음(after)을 출력한다.

반환하는 JSON 형식은 다음과 같다.

![피드백1](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/%ED%94%BC%EB%93%9C%EB%B0%B11.png?raw=true)
![피드백2](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/%ED%94%BC%EB%93%9C%EB%B0%B12.png?raw=true)

#### 4. 리포트 생성 기능
리포트 생성은 ‘3. 피드백 생성’을 통해 반환하는 JSON 값을 기반으로, 생성형AI 기능 중 설명 가능한 AI인 XAI를 통해 제공한다. Prompt Engineering은 ‘3. 피드백 생성‘에서 제공한 “answer“, “user“, “feedback“을 입력 값으로 제공하면 발음에 대한 긍정적인 평가와 주의해야할 부분에 대한 피드백을 생성한다. 


### * 챗봇 기반의 상황극 기능
![3. 챗봇 기반의 상황극 기능](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/3.%20%EC%B1%97%EB%B4%87%20%EA%B8%B0%EB%B0%98%EC%9D%98%20%EC%83%81%ED%99%A9%EA%B7%B9%20%EA%B8%B0%EB%8A%A5.png?raw=true)

해당 서비스에서는 사용자가 몰입하고 싶은 다양한 상황 중 하나를 선택하여 실제로 경험할 수 있다. 선택한 시나리오에 맞춰 생성형 AI가 상황에 알맞은 대화를 제공하고, 사용자의 답변이 문맥에 맞는지 분석해준다. 

또한 TTS와 STT 기술을 활용함으로써, 사용자는 마치 실제 상황에 있는 것처럼 자연스러운 대화를 경험할 수 있게 도와준다.

#### 1. 상황 설정
사용자가 상황극 기능을 시작하면, 어떤 상황에서 대화를 연습하고 싶은지 묻는다. 예를 들어, '도서관에서 책 빌리기', '학교에서 새 친구 사귀기' 등 다양한 일상의 상황을 설정할 수 있다.

#### 2. STT기반의 음성 인식 기능
사용자가 마이크로 말하는 것을 실시간으로 텍스트로 변환한다. 이를 위해 Google의 음성 인식 서비스를 사용한다. 만약 음성 인식에 문제가 발생하면, 그에 대한 오류 메시지를 사용자에게 알려준다.

#### 3. TTS와 ChatGPT를 이용한 상황극 대화 기능
사용자가 대화를 이어나가면서 인공지능(AI)은 적절한 응답을 계속 제공한다. 만약 사용자가 "나가기"라고 입력하면 대화가 종료되고 상황극은 끝나게 된다. 사용자와의 대화 중에 AI는 제공한 응답을 텍스트로 보여주고, 이를 음성으로 변환하여 사용자에게 들려준다. 이러한 과정을 통해 대화가 더욱 자연스럽고 생동감 있게 이루어질 수 있다.

![상황극](https://github.com/yyeongha/Dodam-Dodam/blob/main/img/%EC%83%81%ED%99%A9%EA%B7%B9.png?raw=true)

## 🖥️ 개발환경
### 🖱 환경
* CPU : Intel(R) Core(TM) i5-8265U
* GPU : NVIDIA GeForce RTX 3060 
* CUDA version : 11.8
* PyTorch version : 2.3.0

### 🖱 데이터
* 녹음 및 리포트 제공 서비스
  * [문화공공데이터광장 한국전래동화](https://www.culture.go.kr/data/openapi/openapiView.do?id=391&keyword=%EB%8B%A4%EA%B5%AD%EC%96%B4%EB%8F%99%ED%99%94%EA%B5%AC%EC%97%B0_%ED%95%9C%EA%B5%AD%EC%A0%84%EB%9E%98%EB%8F%99%ED%99%94&searchField=all&gubun=A)

  * [AI Hub 한국어 음성](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=123)

* 챗봇 기반의 상황극 기능 
  * [AI Hub 한국어 대화](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=116) 

  * [AI Hub 주제별 텍스트 일상 대화 데이터](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=543)


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


