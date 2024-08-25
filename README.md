# Defect-Detection-Model-for-Manufacturing-Data
LG aimers, 제품 이상 여부 판별 모델 개발

이 프로젝트는 공정 데이터를 기반으로 제품의 불량 여부를 예측하는 모델을 개발하는 것을 목표로 합니다. 
주요 단계는 다음과 같습니다:

1. Data cleaning and preprocessing
2. Data EDA
3. Model Fit
4. Prediction


## **1. Data Cleaning and Preprocessing**
### 1.1 결측치
- 모든 값이 결측치인 열 제거
- 유니크한 값이 1개인 칼럼 제거
- 60% 이상이 결측치를 가지는 열 제거


### 1.2 Cleaning
- 동일한 값을 가지는 변수 정리
- 패턴을 가지는 변수들 범주화
- 패턴을 가지는 특정 열 변수 데이터 정리

## **2. Data EDA**
### 2.1 파생변수
- Equipment
- Average Pressure

### 2.2 PCA
- 좌표 변수들 중에서 상관계수가 1인 변수들 PCA 진행하여 차원 축소
- 좌표 변수에서 상관계수 1이 아닌 변수들 PCA 진행하여 차원 축소
- CLusting을 통해 유사한 집단 PCA 진행


## **3. Model Fit**
### 3.1 Catboost 
### 3.2 Gradient Boosting
### 3.3 Random Forest 

아직 진행중인 프로젝트임으로 추가 업로드 예정 
