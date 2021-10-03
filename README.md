# 개요

<code>`본 프로젝트는 세종대학교 2021 SW/AI 해커톤를 통해 진행되었습니다.`</code> 

퀀트란 Quantitative 와 Analyst의 합성어로, 수학 및 통계에 기반해 투자 모델을 만들거나 금융 시장 변화 예측을 말합니다. 

- Kospi 시가총액 상위 100개의 주가를 ML/DL 방식을 이용하여 다음날의 주가를 예측하고 종목을 추천합니다.

- Abnormal Detection을 이용하여 이상치를 감지하여 이를 시각화합니다.
- 이상치 감지를 통해 검출된 기간의 뉴스를 NLP를 통해 시각화합니다.
- 효율적인 접근성 고려하여 웹사이트 제작을 통해 서비스를 배포합니다.



### 차별성

- 다양한 변수 사용 - 다른 모델과 다르게, 주가 뿐만 아니라 주가에 큰 영향을 미치는 변수들을 사용
- 개별 모델 사용 - 변동성이 큰 종목장세에서 전략적 대응을 위한 기업별 개별 모델 학습



### 기술스택

- Python - Pandas / Numpy / Matplotliib / bs4 / WordCloud

- ML/DL - LSTM / AutoEncoder ( LSTM / KNN )
- Frontend - HTML / CSS / JavaScripts
- Backend - Django



### 사용 데이터셋 ( 10년치 )

해당 데이터셋 선정이유는 다음 사이트를 참고하세요 ( 이후 추가예정 )

- Kospi 시가총액 100개 기업 주가
- Kospi 외국인 / 기관 수급
- High yield spread
- WTI - Crude Oil Price
- US 500 지수
- 상해 지수
- 미국 10년 금리
- Dollar Index
- 원/달러 환율

