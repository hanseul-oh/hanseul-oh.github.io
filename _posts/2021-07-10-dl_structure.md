---
title: Deep Learning Structure when predict index and share price
excerpt: 국내 주가를 예측할 때, 어떤 구조가 성능이 좋을까?

categories:
  - Data Analysis
tags:
  - [Featuer Selection]

toc: ture
toc_stcky: true
use_math: true
---

시계열 데이터에 많이 사용되는 구조는 LSTM
LSTM이 DNN보다 더 좋은 예측값을 준다면 그 이유가 뭐야?

딥러닝은 여러 주어진 input 데이터에 가중치 행렬과의 연산을 통해 
전날의 종가에 비해 당일의 가격이 얼마나 변했는지를 백분률로 나타낸 값
이평선 같은 경우는 4일 동안의 이평선이라면 가중치가 0.25로 4개 있다면 
따라서 N일간의 가격데이터를 input으로 사용하면 이평선 데이터를 넣지 않아도

다음날 주가에 오늘 주가의 가격변화율이 유의한 영향을 미친다면
가격만 넣으면 전날 주가와 차이는 계산해서 나오는데 














