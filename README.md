# MarchineLearning

## 1. Marchine Learning 개요
  * 역사, 문제점
  * 머신러닝 종류
      - 지도학습 : 데이터에 대한 Label(명시적인 답)이 주어진 상태에서 학습
      - 비지도학습 : 데이터데 대한 Label(명시적인 답)이 없는 상태에서 학습
      - 강화학습 : 지도학습과 비슷하지만 완전한 답(Label)을 제공하지 않음

  * 머신러닝 과정
    <br>
    ![image](https://github.com/JangGunWook/MarchineLearning/assets/119468128/8c4b3eeb-231e-49d9-b0cc-65e698e987c4)
    <br>

## 2. Marchine Learning 일반화, 과대, 과소, KNN
  * 과대 적합 : 훈련 세트에 너무 맞추어져 있어 테스트 세트의 성능 저하
  * 과소 적합 : 훈련 세트를 충분히 반영하지 못해 훈련 세트, 테스트 세트에서 모두 성능이 저하
  * KNN(K-Nearest Neighbors) : 유유상종의 개념과 유사, 특정 데이터 포인트와 가장 가까운 이웃 데이터 포인트를 찾아 분류


## 3. Decision Tree, Label Encoding, One-hot Encoding, Cross validation
  * Decision Tree : 스모고개 하듯이 예/아니오 질문을 반복한느 학습
    <br>
    ![image](https://github.com/JangGunWook/MarchineLearning/assets/119468128/f59ea215-0987-4d08-9f1b-82aae1a88386)
    <br>
  * Label Encoding : n개의 범주형 데이터를 0부터 n-1까지의 연속적 수치 데이터로 표현하는 것이다.
    <br>
    ![image](https://github.com/JangGunWook/MarchineLearning/assets/119468128/fcb41d7e-f428-4c5c-86ca-570f90f782d6)
    <br>
  * One-hot Encoding : One-Hot Encoding은 말 그대로, 하나만 Hot 하고, 나머지는 Cold한 데이터이다.
    <br>
    ![image](https://github.com/JangGunWook/MarchineLearning/assets/119468128/eb8d6cdb-6a52-4558-84c4-f262d1ffb8f8)
    <br>
  * Cross validation :  평가 데이터 나누기를 여러번 반복하여 모델의 안정성을 높이고, 과대적합을 감소시키는 통계적 기법이다.
    <br>
    ![image](https://github.com/JangGunWook/MarchineLearning/assets/119468128/170db2b7-ff94-41af-8cb2-bc927ada34a5)
    <br>

## 4. 앙상블 모델, 그리드 서치
  * Ensemble : 여러 개의 모델을 연결하여 데이터를 학습하고, 모든 모델의 예측 결과를 종합하여 최종결과를 내는 기법
    <br>
    ![image](https://github.com/JangGunWook/MarchineLearning/assets/119468128/d779e282-7fd2-416f-9101-84f7eb49893a)
    <br>
  * GirdSerchCV : 모델 하이퍼 파라미터에 넣을 수 있는 값들을 모두 입력하고, 모든 경우의 수에 대해 모델을 만들고 성능을 평가해 그 중 모델 성능을 가장 높게 만드는 파라미터 값을 찾아준다 


## 5. LinearRegression
  * 데이터 스케일링 :
    <br>
    ![image](https://github.com/JangGunWook/MarchineLearning/assets/119468128/9c1e77f1-4036-4c1f-8802-2d2358f845b6)
    <br>
  * Linear Model(선형모델) :
    <br>
    ![image](https://github.com/JangGunWook/MarchineLearning/assets/119468128/fd2d6587-c8fd-468e-aae2-2e728bb4457f)
    ![image](https://github.com/JangGunWook/MarchineLearning/assets/119468128/d081fc15-3b9f-46ae-b371-dbd6bf9e6d43)

    <br>
  














