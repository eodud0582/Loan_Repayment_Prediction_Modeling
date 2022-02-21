# 대출 위험도 예측 모델 개발 (Loan Repayment Prediction Modeling)

## 프로젝트 배경
- Kaggle Competition

## 프로젝트 목적
- 은행 대출 대상자를 예측하는 알고리즘 개발
- 실제 은행 데이터를 사용하여 **대출을 받으려는 사람이 상환을 할 수 있을지 없을지를 예측**
- 최종 모델은 **일정 기간(2년) 내에 채무 불이행 할지/아닐지 여부**를 출력

## 프로젝트 결과
- **auc score: 0.8975110204309532**

## 데이터 설명
- Kaggle 대회에 공유된 금융 데이터
- 타겟 변수 : SeriousDlqin2yrs
  - 최근 2년 동안 90일 이상 연체한 적이 있는지 여부
  - 값: 1 (연체한 적 있음), 0 (연체한 적 없음)

## 모델링 평가 지표
- roc_auc 점수
