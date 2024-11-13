# AI-CLASS2  

| Title                                      | Value                                                           |
|-------------------------------------------|------------------------------------------------------------------|
| 소속                                      | 가천대학교 IT융합대학 컴퓨터공학과                                |
| 학번/이름                                 | 201935252 나경민                                                |
| 수업 이름                                 | 딥러닝 응용                                                     |
| 교수님                                    | 이명규 교수님                                                   |

---
- 중간고사 공지  https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&bwid=784931  
  [이론]  
인공지능 기초를 위한 FAQ  
https://github.com/MyungKyuYi/AI-class/blob/main/README.md  
+ 추가적인 수업내용
  
[실습]  
csv 파일을 주면, 자신의 github를 참조해서 머신러닝 분류/회귀, 딥러닝 분류/회귀 작성하기  
---

- 하이퍼파라미터 튜닝  
  https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&bwid=785843

- 오토인코더  
  https://machinelearningmastery.com/autoencoder-for-classification/

- CNN, RNN, LSTM
  https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&page=2&bwid=780334  
  https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&page=2&bwid=780377
  
- 머신러닝의 기초 "혼공머신"  
  https://hongong.hanbit.co.kr/%ED%98%BC%EC%9E%90-%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94-%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EB%94%A5%EB%9F%AC%EB%8B%9D/

- 딥러닝에서 **손실함수**와 **활성화함수**의 조합
  https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&bwid=783780

- SVM, DT
  https://medium.com/towardsdev/machine-learning-algorithms-16-support-vector-machine-svm-878c2e1d024f
  https://medium.com/towards-data-science/a-visual-understanding-of-decision-trees-and-gradient-boosting-c6bc53f982ce

- F1-SCORE, RECALL
  https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd


---
- 1주차 과제(9.9 업로드) https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&page=3&bwid=783787
  1. 당뇨병 데이터를 가지고 머신러닝 5가지 분류를 수행. (SVM, LR, RF, DT, KNN)  
  2. 동일한 데이터로 딥러닝 분류 수행하라. (dense layer 만 사용)  
  3. 해당 데이터에서 Outcome을 삭제하고 BMI를 예측하는 회귀를 수행하라.  
  4. 3번과 동일하지만 dense layer만 사용한 신경만으로 회귀를 수행하라.  
     
- 2주차 과제(9.10 업로드) https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&page=3&bwid=784917  
  1. Abalone 데이터로 (ML : classification, regression), (CNN : classification, regression) 진행하기  
    
- 3주차 과제(9.19 업로드) https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&page=2&bwid=789787  
  1. 2주차 과제의 Abalone의 분류와 회귀(classification/regression)를 CNN과 LSTM으로 분류 및 회귀를 작성하라.  
  
- 3주차 **선택 도전과제** 분류를 위한 순환데이터 만들기(split_squance를 수정하시오) https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&page=2&bwid=790057  

- 4주차 과제(9.26 업로드) https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&page=2&bwid=794871  
  1. diabates 당뇨병 분류를 CNN으로 구현, 모델을 저장한 후  
  2. 사전학습 모델로 불러서 추가적인 층 및 출력층 추가하고 미세조정 FINE-TUNING  

- 5주차 과제(10.03 업로드) https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&page=2&bwid=799643  
  1. PCA를 이용해서 diabates 적용해보기 (n수는 자유)  
  2. (수정된 신용카드 거래 소스올리면, 그걸 해보고 수행한 후 응용해서 아래 실습)  
     2-1. DSA데이터에서 (lyingRigh = 480), (lyingBack = 480)을 정상 (normal) jumping(abnormal)을 비정상 데이터로 사용  
     2-2. 두개 (lying+jumping) activity를 섞어서 test  
     2-3. lying만 가지고 훈련하여 AE 구축  
     2-4. 테스트 데이터(lying+jumping)AE에 넣어서 Reconstruction error(입력/출력차이)를 구함  
     2-5. 적당한 threshold값으로 분류수행  
     2-6. accuracy를 구함  

- 7주차 과제(10.17 업로드) https://cyber.gachon.ac.kr/mod/ubboard/article.php?id=859585&bwid=808659 
  1. DSA dataset을 이용해서, 정상데이터(Lying)과 비정상데이터 설정 (다른 jumping이 아니라 activity 선택)  
  2. Encoder와 Decoder의 구조가 같은 오토인코더로 지난주차와 동일하게 이상치 탐지  
  3. Encoder와 Decoder의 구조가 다른 비대칭형 뉴런수로 성능 확인  
  4. DAE를 사용하여 성능확인  
 
- 11주차 과제(구두로 말씀)  
  1. GAN 코드 업로드.  
