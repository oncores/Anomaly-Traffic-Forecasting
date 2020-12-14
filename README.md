# anomaly_traffic_forecasting
- 과제명 : LTE 장비 및 IT 인프라 자산의 효율적 운영을 위한 자가진단 통합 제어 관제 시스템
- 과제기간 : 2019.01.01~2019.12.31
- 수행기관 : 한국산업기술관리평가원/(주)하몬소프트
- 역할 : 참여연구원
- 사용량 예측 모델을 통해 네트워크 장비의 이상 여부를 분류

## traffic forecasting model
- LSTM
- Bi-directional LSTM
- Sequential Attention LSTM

	
## forecasting custom loss
- Quantile loss
- MAE
- MSE

## Input Feature and Data Augmentation
![image](https://user-images.githubusercontent.com/37866322/102147633-671b3500-3eae-11eb-9e82-57c6a6e0662d.png)
![image](https://user-images.githubusercontent.com/37866322/102148146-42738d00-3eaf-11eb-8179-741751c2f3ee.png)

## Research Summary
![ATC](https://user-images.githubusercontent.com/37866322/101491426-10da5d80-39a7-11eb-86c4-365c83ad2e12.jpg)

## Result
- 예측 모델 기반 장비 이상 탐지 및 예측성능 모델 평가
- FVU=1-R2 Score
- N-step : 장비 고장 예측 시점을 5분 단위로 평가
![image](https://user-images.githubusercontent.com/37866322/102148211-6040f200-3eaf-11eb-8afb-ab21294f4e42.png)
