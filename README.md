# review_analysis

## * Playstore review
#### 1) google_play_scraper를 이용하여 구글 플레이 리뷰를 스크레이핑
#### 2) 원하는 컬럼과 년도를 추출하여 분석 범위 내 데이터프레임 생성(2022년 기준, 5개년 추출 위해 2017보다 큰 년도만 추출)
#### 3) konlpy의 Okt 분석기를 이용해 명사 추출 -> 년도별 단어 빈도 추출(단어 빈도 : 리뷰 1개당 최대 1회로 제한)
#### 4) 단어, 년도를 기준으로 정렬한 뒤 csv 형태로 저장
#### code : [playstore_review_scrap](https://github.com/Umhyunbin/review_analysis/blob/659874a5bbfc7f4e9f75578b88257578ad5b39f9/playstore_review_scrap.ipynb)
