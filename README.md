<h1 align="center"> 🙌🏻 자연어 처리(NLP) 🙌🏻 </h1>
🌱 2021.01.23 - 2021.02.10 <br>
🌱 Natural Language Processing_HUFS_AI_CAMP

## ✨ Day 0

'Google Colab' 및 'Slack'의 조작 방법 익히기 <br>
'Numpy, Tensorflow, Matplotlib, Pandas'에 대한 기본 지식 학습하기<br><br>
<p align="center"><img src = "Data/images/day1.PNG" alt="day1" width = "419" height = "343"></p>

## ✨ Day 1

<b>1.1 단어 분류 프로젝트</b><br><br>
sentences를 입력 받아 구성하는 단어가 긍정인지, 중립인지, 부정인지 분류하는 프로젝트를 만들어 본다. <br>
이때 단어의 긍정은 2, 중립은 1, 부정은 0으로 표시하며, 예를 들어 "나는 오늘 기분이 좋아" 라는 문장의 경우 띄어쓰기를 기준으로 split()하여 <b>[1, 1, 1, 2]</b>를 출력한다.<br>
단어 분류 프로젝트는 데이터를 통해 Vocabulary를 생성 -> 학습용 데이터 생성 -> 모델링 -> 학습 -> 평가 -> 예측을 통해 진행된다. 실습 내용은 [1.1 simple word project](https://github.com/bbjoite09/NLP/blob/main/Practice/1.1%20simple%20word%20project.ipynb) 파일에서 확인할 수 있다.<br><br>

<b>📝 1.2 문장 분류 프로젝트</b><br><br>
위의 단어 분류 프로젝트와 비슷하게 입력받은 문장이 긍정인지, 부정인지 분류하는 프로젝트를 만들어 본다.<br>
위와 유사하게, 단어의 긍정은 1, 부정은 0로 표시한다. "나는 오늘 기분이 좋아" 라는 문장의 경우 <b>1 : 긍정</b>을 출력하도록 한다. 실습 내용은 [1.2 simple sentence project](https://github.com/bbjoite09/NLP/blob/main/Practice/1.2%20simple%20sentence%20project.ipynb) 파일에서 확인할 수 있다.

## ✨ Day 2
<b>2.1 Encodding</b><br><br>
첫번째로 데이터를 표현하는 방법에 대하여 학습하였다. Text data의 경우 입력받은 문장을 중복을 제거하여 Tokenizer 한 후 각 Token에 대하여 index를 부여한다. 이후 Encoding을 진행한다. 이때 여러가지의 Encoding 중 One hot encoding에 대한 실습을 진행하였다.<br>
One hot encoding은 위에서 받은 Token의 집합, 즉 단어의 집합을 벡터 차원의 크기로 만들고 원하는 한개의 단어 인덱스에만 1, 나머지 단어들에는 0을 부여하는 벡터 표현 방식이다. 실습 내용은 [2.1 encoding](https://github.com/bbjoite09/NLP/blob/main/Practice/2.1%20encoding.ipynb) 파일에서 확인할 수 있다.<br><br>

<b>2.2 Tokenizer</b><br><br>

<b>📝 2.3 Tokenizer</b><br><br>
my_corpus라는 새로운

## ✨ Day 3
