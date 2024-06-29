# 2024년 날씨 빅데이터 콘테스트 (기상청 주관)
## ⛅ 과제4. 기상에 따른 공동주택 전력 수요 예측
기간 : 2024년 5월 3일 ~ 2024년 6월 28일\
팀원 : 3명(@JAMJAMI98)

## 📋 Data
- 기존 데이터 변수
<img width="810" alt="스크린샷 2024-06-28 오전 11 27 57" src="https://github.com/SUUUUUMIN/2024_Weather_Bigdata_Contest/assets/93477480/1d8aa042-4392-4702-9691-bff6c0f65823">

- 파생변수 생성
  - daily_avg_temp : 일별 평균 온도
  - CDD : 냉방도일 
  - HDD : 난방도일 
  - THI : 불쾌지수 
  - WCI : 바람냉각지수
  - Holiday : 공휴일
  - season : 계절성
  - hour_sin, hour_cos : 시간 변수의 inherently cyclical하다는 특징 활용하기 위해 sin/cos 변환


## 🧶 Modeling
- XGBoost
- LightGBM
- Catboost
- LSTM
- LTSF
