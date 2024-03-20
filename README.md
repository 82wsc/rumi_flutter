# senior_fitness_app : 시니어 웰니스 케어 어플리케이션
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/161b9e9f-89db-4868-b0c3-45ea10172809" width="800" height="450"/>
<br/>
❓Problem : 2017년과 비교하여 2020년 노인실태조사 생활상 변화 통계를 살펴보면, 운동빈도는 감소하고, 우울증도 증가함을 알 수 있다. 자녀 왕래빈도 역시, 감소함으로 노인고립도가 증가하였다. 🤔 <br/>
👍Idea : 
* 신체적 기능 💪🏻<br/>
SFT(Senior Fitness Test)로 60세이상 어르신분의 운동능력을 측정하고, 이를 기반으로 건강 유지 및 개인 맞춤 운동 추천 기능을 제공하여 운동 계획 수립에 도움을 줌.<br/>
※ SFT : 체력구성요소(근력, 지구력, 유연성, 민첩성, 평형성)에 대해 6가지 동작을 평가<br/>
* 정신적 기능🧑‍🤝‍🧑<br/>
어르신 분의 외로움 및 우울감을 낮추기 위해 친구가 될 말동무 봇을 제작함.<br/>
말동무를 음성으로 구현하여 시력 감퇴, 채팅에 익숙하지 않은 어르신분들이 쉽게 대화가 가능하도록 하였음.<br/>

💯 Solution : 초고령 사회에 맞춰 어르신 분들의 건강 유지를 위해 규칙적인 운동을 돕고, 사회적 고립으로 인해 우울감이 높은 어르신들의 외로움을 해소시킬 말동무 서비스를 제공하는 앱을 제작<br/>

## 구현 
#### 시작화면
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/5952e12d-3f14-49bf-908d-6fb327d4c354" width="200" height="350"/> 
</br>

#### 회원가입
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/e02dafa1-2d96-4c7f-a6cb-327e6270836d" width="150" height="350"/>
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/d4a798aa-69a3-4b0c-ab4e-6eb72919f1bc" width="300" height="250"/>
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/604acca9-2f94-428c-baf3-29a9954b41af" width="300" height="250"/> </br>

#### 메인화면 

<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/7cb3dd32-8d88-49aa-b9b4-82958726401d" width="200" height="350"/></br>

#### 운동하기

현재 나이, 신체나이, 측정결과(DB), 추천 운동

<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/9a49e129-e49f-4073-abbc-c59fda077e16" width="700" height="350"/> </br>

예시 영상 시청 후 측정 시작 </br>

<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/e4b6f2b7-7f5f-4da1-841f-e1f0174ae107" width="500" height="350"/>
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/5d16712f-2f44-4e0c-b32c-26cf67783cdc" width="500" height="350"/></br>

#### 말동무
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/0a7cd73a-e80e-4ead-b4e0-d83551bafa73" width="200" height="350"/>
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/49390153-ddab-4c72-8877-3f483d8763e2" width="200" height="350"/></br>

https://github.com/hyobin0726/rumi_flutter/assets/140376727/e4d39234-d30d-46d8-b6f3-2836fc665f9c



## 주요 기능과 로직
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/e3744f07-7717-4cfa-bace-f391cbf3a1a2" width="600" height="300"/>
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/a7d42dfc-cd54-43a2-83c2-b546220d9e05" width="600" height="300"/>
<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/4d3acc58-af63-4617-b031-22f9034e8d8a" width="600" height="300"/>

## 서비스 구조
![image](https://github.com/hyobin0726/rumi_flutter/assets/140376727/edf84ce5-cccc-4435-b5bc-21a1cadf866d)
![image](https://github.com/hyobin0726/rumi_flutter/assets/140376727/a4aa8d8c-a9d9-4ebd-ad88-d5521b9852c7)

## 기술 스택
* Front <br/>
  Dart <br/>
* Back <br/>
  Mysql, ngrok <br/>
* AI <br/>
  python, flask <br/>
  vision- posedetection : goole에서 제공하는 google ML kit 사용 <br/>
  NLP : AI hub(감성대화 말뭉치, 노년층 대상 감성 분류 모델)+github(ChatbotData.csv) 총 83,850개 데이터 학습, <br/>
  GPT-2를 한국어로 학습시킨 SKT가 공개한 오픈소스 KoGPT-2 사용
* 협업툴 <br/>
  notion, github <br/>
## 개발 기간
2023.11~2023.12
## 기획 & 설계
![image](https://github.com/hyobin0726/rumi_flutter/assets/140376727/b542aaea-09ae-4d02-a3f3-a89e663c6add)
![image](https://github.com/hyobin0726/rumi_flutter/assets/140376727/25af05ef-6c67-463e-b2d4-fb1d6ebb19b3)

<img src="https://github.com/hyobin0726/rumi_flutter/assets/140376727/cf96bbc8-2d34-456c-aeb4-9e80eba8ac5c" width="300" height="300"/>
사용자의 무병장수를 기원하며 십장생 중 학(두루미)에서 착안한 자체 제작 캐릭터
