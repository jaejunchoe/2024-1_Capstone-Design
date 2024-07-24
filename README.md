# 2024-1_Capstone-Design

# 🗂 Presentation
## 1. Data
**&ndash; Mixed-type Wafer Defect Datasets (Kaggle) (URL: https://www.kaggle.com/datasets/co1d7era/mixedtype-wafer-defect-datasets)**

* 연구에서 사용할 단일과 이중 혼합 유형의 결함 이미지 데이터
![image](https://github.com/user-attachments/assets/bba3ff88-b11a-46cc-8813-20c1a31dcd4c)
><br/>
* 사용할 데이터셋의 구조와 개수
![image](https://github.com/user-attachments/assets/ef8c52f4-4924-4ee8-acae-ff95454a4a13)


<br/><br/>
## 2. Problem Definition
- 연구동기
![image](https://github.com/user-attachments/assets/c7305bb2-0621-40fc-bc3d-41bd9ca6aa78)


<br/><br/>
## 3. Modeling
- AI 모델 구현 로드맵
![슬라이드7](https://github.com/user-attachments/assets/2efc3049-f7e8-4c9f-92ff-2b42f964e08a)
![슬라이드10](https://github.com/user-attachments/assets/bbe4bc64-6fb3-4877-8887-3b1998ad12de)

<br/>

- 사용 알고리즘: `Vision Transformer`, `KNN`

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



