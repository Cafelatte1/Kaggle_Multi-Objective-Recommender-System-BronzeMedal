## 🏆 Kaggle Multi Objective Recommender System - Top10% BronzeMedal Solution
![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Success-green)

## Introduction
- 고객 로그 정보를 활용해 미래의 고객 interaction(클릭, 카트, 주문)을 예측하는 task
- [Solution Link](https://www.kaggle.com/code/cafelatte1/otto-recsys-ranking-with-public-nbs-v4-valid?scriptVersionId=117615534)

## Dataset
- 고객 로그

## CV Strategy
- 최근 7주일 데이터를 검증데이터로 설정 (holdout)

## Modeling
- 과거 아이템 재정렬 / 고객&아이템 관계 기반 / 딥러닝 기반 3가지 카테고리의 알고리즘들을 앙상블 하여 최종 추천 아이템을 예측
![image](https://github.com/user-attachments/assets/898e5d4f-3176-4572-8ef4-367149a07989)

## Core Strategy
### 1. Trend Items by Time Window
- 가장 최근 시간대의 인기있는 제품을 추천했을 시 유의미한 성능을 보임
- [Notebook Link](https://www.kaggle.com/code/cafelatte1/otto-recommendation-trend-items-by-time-windows)
### 2. User-Based Filtering
- 특정 User가 과거에 구매한 아이템에 대해 함께 구매했던 다른 고객들의 아이템들을 추천하는 알고리즘
- User 관점의 정보를 이용해서도 유의미한 결과를 보여줄 수 있음을 시사
- [Notebook Link](https://www.kaggle.com/code/cafelatte1/otto-user-based-filtering)

