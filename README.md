# 빅데이터와 머신러닝

## Data Science Process
>> 데이터 수집 -> 데이터 전처리 -> 데이터 분석 -> 데이터 예측 -> 데이터 시각화/서비스화

### 데이터 수집
- Database
- File(CSV, XML, JSON)
- Web crawling
- IoT sensor data
- Survey

### 데이터 전처리(Preprocessing)
- 결측치 처리
  - 데이터 삭제
  - 다른 값으로 대체 (최대값, 최소값, 중앙값)
  - 예측 모델을 활용한 값 삽입
- 이상치 처리
  - 입력 오류(데이터 삭제, 다른 값으로 대체)
  - 자연 발생(feature 추가)
- Feature Engineering(특성공학)
  - 데이터를 본인 입맛에 맞게 변형
  - scaling(feature의 단위를 변경)
  - binning(수치형 -> 범주형)
  - transform(feature를 분리하거나 연산- 날짜, 주중/주말)
  - encoding(범주형 -> 수치형)

### 데이터 분석(EDA:탐색적 데이터분석)
- 각 변수가 어떤 의미인지 파악
  - meta data
  - data description
- 범주형
  - 성별, 혈액형, 성공여부, 학점, 효과정도 등
- 수치형
  - 발생횟수, 학급인원, 키, 몸무게, 혈압 등
- 기술통계
  - 최대값, 최소값, 최빈값, 평균값, 중앙값, 분산, 표준편차, 사분위수 등
- 변수간 상관관계, 독립여부 확인

### 데이터 예측 (Machine Learning)
- 지도학습
  - Linear regression
  - SVM
  - Decision tree
  - KNN
  - Ensemble model 등등
- 비지도학습
  - clustering
  - 차원축소
- 딥러닝
  - 음성인식, 영상인식, 자연어처리 등

### 데이터 시각화/서비스화
- 시각화
  - 산점도, 막대그래프, 파이그래프, box-plot, 히스토그램, 히트맵 등
- 서비스화
  - 웹서비스, 모바일 서비스, desktop application 등


## 데이터의 중요성
>> 데이터 분석가는 80% 이상의 시간을 데이터 수집/전처리에 사용한다
>> garbage in garbage out : 좋은 자료를 모으고, 적정하게 정리하여 넣지 않으면 가치를 발견하기 어렵다.

## 단계별 python 패키지
- 수집
  - BeautifulSoup, Selenium, PyMySQL, PyMongo 등
- 전처리
  - Pandas, Numpy 등
- 분석
  - Numpy, Pandas, Matplotlib, Seaborn 등
- 학습
  - SKlearn, SparkML, Tensorflow, Keras 등
- Commution/Reporting/Building Data Product
  - Django, Seaborn,, Flask 등

## 분석에 특화된 라이브러리
### Numpy
- 고성능 과학계산을 위한 데이터 분석 라이브러리
- 빠르고 효율적인 벡터 산술연산을 제공하는 다차원배열 제공(ndarray 클래스)
- 반복문 없이 전체 데이터 배열 연산이 가능한 표준 수학 함수(sum(),mean() 등)

### Pandas
- 행과 열로 구성된 표 형식의 데이터를 지원하는 라이브러리