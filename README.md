# Predict_Top10_Popular_Chart

프로젝트 소개 : https://rahites.tistory.com/103

1. 웹크롤링&데이터분석  
: [멜론의 시대별차트](https://www.melon.com/chart/age/index.htm?chartType=YE&chartGenre=KPOP&chartDate=1990)를 이용하여 1990년부터 2021년까지의 Top30곡 제목, 가수, 가사를 크롤링, 기본적인 텍스트 분석을 진행

2. 토픽분석  
: 크롤링한 데이터를 가지고 기본적인 토픽 모델링 진행

3. 피처생성  
: 크롤링한 데이터를 이용하여 1990년 ~ 2019년의 텍스트 분석한 결과를 feature로 생성  
  (Top10안에 든 곡들은 1, 들지 않은 곡들은 0으로)

5. 모델링  
: 생성한 피처 데이터를 활용해 머신러닝 모델링 -> 인기차트 Top10 예측
