# 베스트셀러 이름과 트렌드모델의 연관성\

-------------------------

## 배경
독자들의 도서 선택 이유가 책 내용보다 트렌드와 연관이 되어 있다는 기사를 토대로 프로젝트를 진행하게 되었다.

--------------
## 목차
1. 알라딘 베스트셀러 크롤링
2. 다음 뉴스 크롤링
3. 블로그 크롤링
4. 자연어 처리 모델 모델링
-------------------

## 알라딘 베스트셀러

2022년은 자료가 충분하지 않아 제외하였고 2016~2021년까지 10개년을 크롤링을 했다.


이 과정에서 중복이 되는 부분은 삭제하였다.

-------------------------

## 다음 뉴스 크롤링

네이버보다 크롤링을 쉽게 하여서 선택하였다


동적 크롤링을 사용하였고, 베스트셀러 이름과 관련된 연도의 기사와 섹션을 크롤링 하였다.


-----------------------

## 블로그 크롤링

네이버 블로그를 크롤링 하였다.


동적크롤링을 사용하였고, 검색어에 해당 키워드 + 도서(ex. 영유아 도서)로 검색하여 독자가 자주 쓰는 단어를 검색하여 크롤링하였다.

--------------------

## 자연어 처리 모델

kobert 모델을 사용하여 모델링을 하였다.


모델은 accuracy를 기준으로 판단하였고 결과 약 5퍼센트정도 차이가 남을 알 수 있었다.




