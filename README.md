"# DeepLearn" 

## 1주차(diabetes)
1. 당뇨병 데이터를 가지고 머신러닝 5가지 분류를 수행.

(SVM, LR, RF, DT, KNN)

2. 동일한 데이터로 딥러닝 분류 수행하라. (dense layer 만 사용)

3. 해당 데이터에서 Outcome을 삭제하고 BMI를 예측하는 회귀를 수행하라.

4. 3번과 동일하지만 dense layer만 사용한 신경만으로 회귀를 수행하라.

## 2주차(abalone)
전복 데이터를 가지고,

머신러닝 분류, 회귀

신경망 분류, 회귀를 각각 수행하라

## 3주차(abalone)
분류, 회귀를 CNN과 LSTM으로 분류 및 회귀

## 4주차
diabates 당뇨병 분류를 CNN으로 구현하고

모델을 저장한 후에

사전학습 모델로 불러서 추가적인 층 및 출력층 추가하고

미세조정 fine-tunning 

## 5주차

- 1st 실습

PCA를 이용해서 diabates 적용해보기

(n수는 자유)



- 2nd AE 실습

(수정된 신용카드 거래 소스올리면, 그걸 해보고 수행한후

응용해서 아래 실습)

1. DSA데이터에서 

lyingRigh                  480

lyingBack                  480
을 정상 (normal) jumping(abnormal)을 비정상 데이터로 사용

2. 두개 (lying+jumping) activity를 섞어서 test 

3. lying만 가지고 훈련하여 AE 구축

4. 테스트 데이터(lying+jumping)AE에 넣어서 Reconstruction error(입력/출력차이)를 구함

5. 적당한 threshold값으로 분류수행

6. accuracy를 구함

## 6주차

-  DSA dataset을 이용해서, 정상데이터(Lying)과 비정상데이터 설정 (다른 jumping이 아니라 activity 선택)

- Encoder와 Decoder의 구조가 같은 오토인코더로 지난주차와 동일하게 이상치 탐지

- Encoder와 Decoder의 구조가 다른 비대칭형 뉴런수로 성능 확인

- DAE를 사용하여 성능확인
