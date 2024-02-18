# Week 7
7주차 코드들을 저장할 디렉토리 입니다.

## 7주차의 과제
* 이번 7주차에는 한국어 자연어 처리의 기본과 순환신경망의 개요에 대해 학습해 보았습니다.
* 주어진 dataset 폴더 내의 데이터를 활용하여 자연어 데이터 분석 및 순환신경망을 설계 및 훈련을 진행해 봅시다.
* 이후 `test`데이터를 예측하여 높은 예측성능을 얻어봅시다!
* **`쇼핑몰 리뷰 평점 예측 문제`**
  1. train.csv : 학습 데이터
     * id : 샘플 아이디
     * reviews : 쇼핑몰 리뷰 텍스트
     * target : 상품 평점
  2. test.csv : 테스트 데이터
     * id : 샘플 아이디
     * reviews : 쇼핑몰 리뷰 텍스트
  3. sample_submission.csv : 제출 양식
     * id : 샘플 아이디
     * target : 상품 평점
  * target 평점 분류 : 1,2,3,4,5점(**총 5개 범주**)

* 데이터 출처
  - [네이버 쇼핑](https://shopping.naver.com/)
* `test.csv`파일 내의 데이터셋에 대해 예측한 결과를 `sample_sumission.csv`파일에 작성하여 다음 사이트에 접속해 제출해 보세요!
  * [쇼핑몰 리뷰 평점 예측 대회](https://dacon.io/competitions/official/235938/overview/description)