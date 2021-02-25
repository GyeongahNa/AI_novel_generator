## AI_novel_generator

본 프로젝트는 경희대학교 `소프트웨어융합개론`을 수강하며 진행하였습니다.

### 프로젝트 소개

AI_novel_generator는 웹소설을 스스로 작성하는 AI를 구현하는 것을 목표로 한다. AI 글쓰기는 자연어 처리와 딥러닝의 주요 연구 분야로, 언어모델과 데이터 학습을 통해 AI가 스스로 글을 작성할 수 있도록 한다.
AI의 창의성과 문장구성능력에 대하여는 많은 이견이 있지만, AI가 글을 생성하는 것은 현실적인 이야기가 되었다. 
본 프로젝트에서는 대량의 소설(텍스트) 데이터를 수집 및 전처리 하고, 인공신경망 모델을 이용하여 데이터를 학습시켜 웹소설 생성 AI를 구현하였다.<br><br>

### 사용 언어 및 오픈 소스
- Python
- Jupiter notebook<br><br>

### 데이터 수집 및 전처리
- [작가후기]와 같이 웹소설의 내용과 관련이 없는 부분 삭제,
- 작가들마다 다른 형식을 취하고 있는 부분 통일(대화체의 표시 방식 등)
- 맞춤법 교정
- 텍스트 정제 후 의미 단락으로 구분<br><br>

### 모델 구성 및 학습
- 사용한 모델: LSTM, RNN
- LSTM의 echos, iteration, batch_size 파라미터 조정<br><br>

### 구현 결과

```
Generating text after epoch: 39
...Diversity: 0.2
...Generating with seed: ", 원단은 왜 사가는 거야?” 레오니드 친구들 중 공부를 잘할 것처럼"
...Generated: 

일어나는 그에게 한 대 저런 말을 하는 사람은 내가 이런 말이야.” 
아, 아니 아니. 그렇다고 그 말이 한 번 대회 제 목숨이 있는 거야?” 
“그런데 나한테 아니라 말하자. 그런 거지? “아, 그런 거고요!” 
“그래, 이거 나 자, 이 자식이나 비약이야. 그런 거라면, 그런 게 아니겠는가. 
그런 이들이 아니겠는가. 그런 게 뭐라고?” “아, 아니 아니. 그런 게 아니겠는 것이 아닌가. 
그런데 그 말에 이런 말들을 하는 인물이라면, 나는 그런 이들이 내게 들어오지 않을 그런 기숙사의 비약이야은 없었지만, 
나는 그런 도로 내게 된다 하는 그 사람은 기사의 맹세를 맺어줄 수 있는 그 녀석이 
그런 이 마법사 내가 이어를 붙잡은 채 대회 소파에 돌던 눈래를 이었다. 
그리고는 그러면 그런 아처
```
<br>

### Details
> [결론 / 코드 및 보고서](https://github.com/GyeongahNa/AI_novel_generator/blob/main/codes.ipynb)
> 학습에 사용된 데이터는 저작권 보호를 위해 비공개하였습니다.
