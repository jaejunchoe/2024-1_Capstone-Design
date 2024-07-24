# 2024-1_Capstone-Design
**- 주제:** `Vision Transformer와 유사도 기반 반도체 혼합결함유형 예측`
<br/>

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

     (1) 결함 예측 결과
     ![image](https://github.com/user-attachments/assets/c78011fe-b602-4396-af2a-7008e7d2100b)



     (2) 선행연구와의 비교
     ![image](https://github.com/user-attachments/assets/57c4a5be-9563-42bb-a79f-94ccde4042f3)

<br/><br/>
## 5. Conclusion & Comment
- 기존 동일 컨셉을 가진 연구보다 Edge-Loc 관련 결함유형에서 더 높은 수치의 예측률을 보여주었다.
- 해당 주제의 경우 CNN을 주로 사용하는데 Vision Transformer로 구현해보았다.
- 특정 결함은 어느 정도 탐지하지만 대다수의 결함유형을 탐지하는데 있어서 좋은 성능을 보이지 못했다.
- Model 구현에 있어서 파라미터들의 최적값을 찾지 못했다.
- 특히, Scratch와 Edge_Loc에서 가장 낮은 수치가 나왔는데, 해당 두 결함유형은 타 결함에 비해 굉장히 두껍게 형성되지않고 얇게 형성되는 데이터임을 확인했다. 이를 통해 얇게 형성되는 결함 유형 탐지에는 부적합하다.




