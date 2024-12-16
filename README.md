# SKN07-2nd-2Team
### 2nd Project - Telco Customer Churn / 통신사 고객 이탈 예측
#### 팀원소개
|윤수민|이재철|박민혁|송문택|
|---|---|---|---|
|![숨](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-2Team/blob/main/image/%EC%88%A8.jpg)|![나](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-2Team/blob/main/image/%EA%B5%BF%EB%AA%A8%EB%8B%9D.jpg)|![민](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-2Team/blob/main/image/%EB%AF%BC%ED%98%81.jpg)|![송](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-2Team/blob/main/image/dd.jpg)|
|풀스택|전처리, 모델구축|EDA, 전처리|분석|

---

# 프로젝트 개요

통신사에서는 매년 상당한 고객이 서비스를 해지(이탈)하며, 이는 기업의 수익성과 고객 유지 비용에 큰 영향을 미칩니다. 고객 이탈을 사전에 예측하고 이를 방지하기 위한 전략을 세우는 것은 통신사의 지속 가능한 성장에 필수적입니다. 본 프로젝트는 Kaggle의 Cell2Cell 데이터를 활용하여 딥러닝 기반의 고객 이탈 예측 모델을 개발하는 것을 목표로 합니다.

* 기존 통신사 고객들의 데이터를 활용하여 이탈(Churn) 을 예측, 고객들의 이탈과 각 특성들의 상관계수를 시각화
* 통신사 고객의 정보를 활용하여 신규 고객의 이탈 예측 모델을 구축

## 필요성

1. 고객 유지 비용 절감
  고객을 유지하는 비용은 새로운 고객을 확보하는 비용보다 훨씬 낮음. 고객 이탈을 사전에 예측 시 효율적인 자원 배분이 가능.

2. 수익성 강화
  이탈 가능성이 높은 고객을 조기에 식별, 맞춤형 대책을 마련함으로써 장기적인 수익성을 높일 수 있다는 기대.

3. 데이터 기반 의사결정
  데이터를 활용한 예측 모델은 고객 행동을 더 잘 이해하고, 통신사 서비스의 경쟁력을 강화하는 데 기여.


## 프로젝트 목표

1. 고객 이탈 예측 모델 개발:
Kaggle의 Cell2Cell 데이터를 활용하여 딥러닝 기반의 고객 이탈 예측 모델을 구축합니다.
다양한 딥러닝 모델 (MLP, RNN, CNN 등) 을 고려하여 데이터 특성에 가장 적합한 모델을 선택합니다.
하이퍼파라미터 튜닝을 통해 모델의 성능을 최적화합니다.
모델 학습 및 평가 과정에서 정확도, 정밀도, 재현율, F1-score, AUC 등의 지표를 활용합니다.

2. 고객 이탈 요인 분석:
SHAP, LIME 등의 방법을 사용하여 모델의 예측 결과를 해석하고, 고객 이탈에 영향을 미치는 주요 특성을 파악합니다.
고객 이탈과 각 특성 간의 상관관계를 분석하고 시각화합니다.

3. 이탈 방지 전략 제시:
예측된 이탈 고객에게 제공할 수 있는 맞춤형 프로모션, 서비스 개선 등의 이탈 방지 전략을 제안합니다.
고객 세분화를 통해 각 세그먼트별 특징을 분석하고, 세분화된 고객 그룹에 따른 효과적인 이탈 방지 전략을 수립합니다.



![Gallup 국내 스마트폰 관련 조사 2012-2024](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-2Team/blob/main/image/%EC%8A%A4%EB%A7%88%ED%8A%B8%ED%8F%B0%20%EC%82%AC%EC%9A%A9%20%EC%B0%A8%ED%8A%B8.png)
