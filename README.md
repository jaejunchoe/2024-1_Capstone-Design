# 2024-1_Capstone-Design

# 🗂 Presentation
## 1. Data
1. 구미 에너지자급자족사업 참여기업 A사 2023.07.26 시간별 에너지 사용량 데이터
2. 한국전력공사 데이터 - 2020~2022년 데이터톤 DB(전력사용량, 태양광 발전) + 전력사용량은 1시간 간격, 태양광 발전은 15분 간격
3. 수요 및 설문조사 데이터 - 2023년 구미산업단지공단 스마트에너지클러스터 기업 설문조사 및 수요조사 

<br/><br/>
## 2. Problem Definition & Service Design
- '스마트에너지클러스터 기업 설문조사 및 수요조사'에 대한 분석
![그림2](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/263efd29-44fa-4133-be35-2c3102746fa1)

<br/><br/>
## 3. Modeling
- AI 모델 구현 로드맵
![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/b790f4db-db7f-46ac-b2f4-7a73f2e42b43)

<br/>

- 사용 알고리즘
  
(1) Linear Models (선형모델) – 'Linear Regression', 'SVR'

(2) Neural Networks (인공신경망) – 'Neural Network', 'MLPRegression'

(3) Ensemble Models (앙상블) – 'Random Forest', 'Neural Network', 'Voting', 'Stacking'

(4) Gradient Boosting (그래디언트 부스팅) – 'LGBM Regression', 'Gradient Boosting Regression'

(5) RNN – 'LSTM'

(6) KNN - 'KNN'

<br/><br/>
## 4. Data Analysis And Results 
- Clustering & AI Model 학습 결과

  **최적 예측 모델** = `Ensemble Model` 


     (1) 구미산단 데이터톤 전력사용량 데이터
     ![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/4c01505b-8f5a-4e1f-882f-9826820a92cd)



     (2) 구미산단 데이터톤 태양광 발전량 데이터
     ![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/3271426a-e849-440e-bb21-a1c0e6078cbb)



     (3) 구미 에너지자급자족사업 참여기업 A사 전력량 데이터
     ![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/81966e72-1443-41c7-b2b9-28e19919435f)

<br/><br/>
## 5. Conclusion & Comment
- 데이터의 크기 및 규모가 크고 개인 노트북을 사용하기에 모델 실행과 디버깅을 하기에 많은 시간이 소요되어 어려움이 존재했다.
- 팀원 모두가 데이터톤의 경험이 전무했기에 EDA에서 많은 시간이 소요되었다. 특히, 전력량의 시차 연관성을 파악에 많은 고민을 했다.
- Clustering에서 K-Means Clustering으로만 진행하다가 교수님의 자문을 통해 시계열 클러스터링을 통해서 비슷한 패턴을 갖는 기업끼리 Clustering을 하니 훨씬 수월하게 진행되었다. 
- 여러 알고리즘들을 구현 및 적용하여 결과를 비교하면서 해당 데이터의 최적 알고리즘을 도출할 수 있었다.
- 1가지의 알고리즘을 사용한 것과 여러 알고리즘을 활용하는 Ensemble Model의 평가지표값이 차이가 크게 존재하지 않았다.



