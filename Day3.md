# 3일차

-----

## Deep Learning

### 등장배경

> 기존의 Machine Learning(중에서도 Logistic)으로 AND 연산과 OR 연산은 가능했지만, __XOR연산__은 구현이 불가능했다.    
>
> 그러던 중 1969년, MIT Marvin Minsky 박사(전세계 AI 최고 권위자 중 한명)가 하나의 퍼셉트론는 XOR연산을 절대 구현할 수 없다고 말하며 퍼셉트론이 여러개(Multi layer) 있어야 구현할 수 있다고 말했다. 하지만 학습 방법이 너무 어려워서 지구상 누구도 학습이 불가능하다고 말합니다.  그래서 이후 AI는 침체기에 진입한다.
>
> 1974, Paul Werbos가 한개의 층을 여러개로 나누어서 학습을 시킬 수 있다는 __Backpropagation__ 제안했지만, 학회의 반응이 좋지 않았다.  1982년에 다시 말했지만 또 반응이 없었다.
>
> 1986년, Hinton박사가 Backpropagation이 가능하다는 것을 공언 해 주면서 AI가 다시 각광받기 시작하고, 연구가 다시 시작됩니다.
>
> 이후 Backpropagation이 layer가 많아질 경우 학습이 잘 되지 않는다는 것을 발견하고 AI와 다른 다양한 이론(SVM, Random Forest, etc)들이 등장하기 시작합니다.
>
> 캐나다에서 CIFAR를 설립하며, 전세계 AI 연구가들을 불러들여 연구를 시작했는데 그 중에는, 1987년 이주한 Hinton교수도 포함되었다. 그로부터 10년 후, 기존의 Backpropagation 방법이 잘 되지 않았던 이유를 2가지 발견하였다. 
>
> 1. 초기값 (w, b) 세팅 불량. 
> 2. Layer 수의 부족
>
> 이 두가지 문제를 해결하며 AI 연구는 다시 활성화 되기 시작했고, Deep Nets, __Deep Learing__으로 __Rebranding__ 후 전세계적인 인기를 가져오게 되었다. ___~~사실 예전부터 있던 것~~___





## 1. 환경설정

### 1) Anconda 설치 및 가상환경 설정

### 2) 라이브러리 설치

​	* nb-conda를 설치

### 3) 작업 디렉토리 설정 및 경로설정

### 4) Jupyter-notebook 환경설정 및 실행

---



## 2. Data-analysis 기초 이론

### 1) 빅데이터 정의

### 2) 빅데이터 분석

1. EDA (탐색적 데이터 분석) => 데이터 분석의 가장 **__기본__**
   -> 사실(data)를 바탕으로 그 안에 내재된 내용을 알아내는 것
   -> 통계적 가설검증(statistical hyphotheisis testing) 사용 _ (일원분석, 이원분석, 아노바 등..)
2. Machine Learning => prediction
     : 기존에 있는 데이터를 바탕으로 학습하는것 _ 여기부터는 예측(prediction)이 들어간다.
3. Deep learning (Machine learning 심화)



### 3) Python

-> 파일로 넘어가서 설명합니다.

------

## +a

1. Data 분석이 왜 필요한가?

   1. Amazon의 서적 추천 시스템 : 전체 매출의 30%이상
   2. NETFLIX의 추천시스템
   3. 자율주행
   4. 석유 정제과정 학습

2. Why python?

   1. 상대적으로 쉬운 언어
   2. Interactive Programming이 가능
   3. 강력한 데이터 분석 Library
   4. Open source
   5. R언어에 비해 범용적 사용이 가능
   6. 주의) 하위 호완성 없음 (python 2 vs. python 3)

   

   **R은 분석만 하기에 좋고, python은 분석 결과를 확장하기에 좋다.**