# LG Aimers 7th - 요식업장 메뉴별 수요 예측

LG Aimers 7기 Phase 2 오프라인 해커톤 참여 프로젝트입니다. (참가팀 중 **상위 12%** 기록)

## Overview
약 2년 치의 요식업장 시계열 데이터를 바탕으로, 각 메뉴별 향후 수요를 정확하게 예측하는 머신러닝/딥러닝 모델링 프로젝트입니다. 주어진 데이터의 패턴을 분석하고 대회 평가 산식에 최적화된 모델을 구축하는 것을 목표로 진행했습니다.

## 📂 Repository Structure
- **`LG Aimer 7th 최종코드.ipynb`** : 데이터 전처리, 피처 엔지니어링, 모델 학습 및 평가 파이프라인이 모두 포함된 최종 주피터 노트북 소스 코드입니다.
- **`업장별 판매량 데이터 시각화 분석.pdf`** : 데이터 분석 인사이트, 모델링 전략, 시행착오 및 문제 해결 과정 등 팀의 전체 프로젝트 진행 과정을 상세히 정리한 문서입니다.
  
## My Role
- 데이터 전처리 및 탐색적 데이터 분석(EDA)
- 피처 상관관계 분석 및 파생 변수(Feature) 도출
- 대회 평가 산식(SMAPE)에 최적화된 예측 모델 구축 및 성능 튜닝

## 🛠 Tech Stack
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>

## Key Process
- **Data Preprocessing:** 2년 치 시계열 데이터의 결측치 및 이상치 처리, 시계열 포맷팅
- **Feature Engineering:** 메뉴별 수요 패턴 및 외부 요인 간의 상관관계 심층 분석을 통한 유의미한 변수 생성
- **Modeling & Optimization:** 여러 예측 모델을 교차 테스트하고 끈질긴 하이퍼파라미터 튜닝을 진행하여 최종 **SMAPE 0.515** 달성

## Modeling Pipeline
1. `Data Load` : 제공된 원본 데이터 및 외부 데이터 로드
2. `EDA & Preprocessing` : 데이터 분포 확인 및 정제
3. `Feature Engineering` : 시계열 특성을 반영한 변수 확장
4. `Model Training` : 시계열 예측에 특화된 모델 학습
5. `Evaluation` : 평가 산식(SMAPE) 기반 모델 성능 검증
6. `Prediction` : 최종 수요 예측 결과 산출

## What I Learned
- **데이터 분석의 집요함:** 낯설고 복잡한 시계열 데이터 앞에서도 쉽게 타협하지 않고, 데이터 전처리부터 모델의 구조까지 끝까지 원인을 파고들어 성능을 개선하는 실전 문제 해결 능력을 체득했습니다.
- **Metric 기반의 최적화:** 단순한 모델의 적용을 넘어, 대회의 핵심 평가 산식과 데이터의 고유한 특성에 맞춘 세밀한 튜닝이 최종 예측 성능에 결정적인 영향을 미친다는 것을 배웠습니다.
