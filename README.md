# network-intrusion-classification

Classification model for Intrusion Detection System (IDS)

네트워크 침입 감지를 위한 분류 모델 

![thumbnail](/ex_column.png)


## 목적

1. 패킷 데이터를 통해 네트워크 침입 여부를 판단하는 모델을 개발합니다.
2. 제공된 데이터를 지도학습한 분류 모델들을 개발합니다.
3. 특히 트리 기반의 모델을 앙상블하여 결과치를 최대화합니다.

## 데이터 및 참고문헌
- Intrusion Detection Evaluation Dataset (CIC-IDS2017)
- Tree-Based Intelligent Intrusion Detection System in Internet of Vehicles (L. Yang, A. Moubayed, I. Hamieh and A. Shami, 2019)

## 주요 기능
1. 데이터 전처리, 샘플링 및 정규화 (`01_compact_data.ipynb`)
2. Logstic 회귀, Decision Tree, Random Forest, XGBoost로 데이터 분류 (`02_model.ipynb`)
3. 모델들을 앙상블하여 최적 모델 도출 (*test accuracy: 0.9978*)
