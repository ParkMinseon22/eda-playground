# 전세계 행복 지수 (2015 ~ 2024) EDA

World Happiness Report (2015–2024) 데이터를 기반으로 팀원들이 수행한 EDA 결과를 모아
통합 리포트(EDA Report)를 완성하는 프로젝트입니다.

- 데이터: World Happiness Report (2015–2024)
- 목표: 행복 점수/순위 변화 패턴, 주요 지표 관계, 변동성, 코로나 전후 비교를 종합적으로 정리
- 산출물: 개인별 분석 노트북 + 취합 리포트(예정)

---

## Kaggle Dataset
- 2015 ~ 2019: https://www.kaggle.com/datasets/unsdsn/world-happiness
- 2020 ~ 2024: https://www.kaggle.com/datasets/samithsachidanandan/world-happiness-report-2020-2024

---

## 팀원

| GitHub | dhksrlghd | rusidian | nobrain711 | imseunghyeon264 | ParkMinSeon22 | ch3477-sudo |
|---|---|---|---|---|---|---|
| Profile | @dhksrlghd | @rusidian | @nobrain711 | @imseunghyeon264 | @ParkMinSeon22 | @ch3477-sudo |
| Name | 홍원기 | 장한재 | 조동휘 | 임승현 | 박민선 | 윤찬호 |

---

## Final Outputs (Work in Progress)
- 통합 데이터셋: `data/happiness_2015_2024.csv`
- 최종 취합 리포트: (업데이트 예정)
- 핵심 인사이트 요약: (업데이트 예정)

---

## Reports / Notebooks

### 1) 데이터 통합/정제
- `HongWanGi/01_World_Happiness.ipynb`
- `YunChanHo/01_merge_standardize.ipynb`

### 2) 전체 EDA 리포트
- `YunChanHo/02_eda_report.ipynb`
- `ParkMinSeon/eda_report.ipynb`

### 3) 변동성 분석 + 코로나 전후 해석
- `JangHanJae/eda_volatility_covid_interpretation.ipynb`
- `JangHanJae/eda_volatility_covid_interpretation.md`

### 4) 추가 분석/정리
- `LimSeungHyeon/eda_analysis.ipynb`
- `LimSeungHyeon/manual.md`

---

## EDA Report Structure (Team Standard)
최종 취합 리포트는 아래 구조를 기준으로 정리합니다.

- Executive Summary (핵심 결론)
- Introduction (분석 목적/질문)
- Data Overview (스키마 통일, 컬럼 정의)
- Data Quality (결측/중복/타입/이상치)
- Descriptive Statistics (기술통계/분포)
- Univariate Analysis (수치/범주)
- Bivariate Analysis (관계/비교)
- Correlation Analysis (상관/해석)
- Volatility Analysis (rank/score 변동성 Top 국가)
- COVID Before/After (2015–2019 vs 2020–2024)
- Conclusions & Recommendations
- Appendix (추가 분석/참고)