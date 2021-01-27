<h1 align="center"> 🙌🏻 자연어 처리(NLP) 🙌🏻 </h1>
2021.01.23 - 2021.02.10 <br>
Natural Language Processing_HUFS_AI_CAMP

## ✨ Day 0

'Google Colab' 및 'Slack'의 조작 방법 익히기 <br>
'Numpy, Tensorflow, Matplotlib, Pandas'에 대한 기본 지식 학습하기<br><br>
<p align="center"><img src = "images/day1.PNG" alt="day1" width = "466" height = "382"></p>

## ✨ Day 1

1. 단어 분류 프로젝트<br>
sentences를 입력 받아 구성하는 단어가 긍정인지, 중립인지, 부정인지 분류하는 프로젝트를 만들어 본다. <br>
이때 단어의 긍정은 2, 중립은 1, 부정은 0으로 표시하며, 예를 들어 "나는 오늘 기분이 좋아" 라는 문장의 경우 띄어쓰기를 기준으로 split()하여 <b>[1, 1, 1, 2]</b>를 출력한다.<br>
단어 분류 프로젝트는 데이터를 통해 Vocabulary를 생성 -> 학습용 데이터 생성 -> 모델링 -> 학습 -> 평가 -> 예측을 통해 진행된다.<br>

2. 문장 분류 프로젝트<br>
위의 단어 분류 프로젝트와 비슷하게 입력받은 문장이 긍정인지, 부정인지 분류하는 프로젝트를 만들어 본다.<br>
위와 유사하게, 단어의 긍정은 1, 부정은 0로 표시한다. "나는 오늘 기분이 좋아" 라는 문장의 경우 <b>1 : 긍정</b>을 출력하도록 한다.
