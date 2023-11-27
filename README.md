# mHealthApp-review-textmining_colab
###### 권소연 교수님 '소셜 애널리틱스' 수업 자료

# 1. 프로젝트 소개
### ✅ 참고 자료
https://heytech.tistory.com/401 (티스토리) <br>
https://github.com/park-gb/mHealthApp-review-textmining (원본 깃허브 레포) <br>

해당 자료는 heytech님의 ‘LDA 토픽 모델링을 활용한 앱 리뷰 분석 프로젝트’를 변형하여 인스타그램 앱을 분석하였고,
Python과 Jupyter가 익숙하지 않은 학생들을 위해 자세하게 분석해 놓았으며, Colab 환경에서 작동할 수 있도록 코드 변형을 거친 repo입니다.


# 2. 폴더 구조
## 1) result
프로젝트의 코드를 모두 완료했을 때 보실 수 있는 4개의 파일들입니다. <br>
(1) Ida_result_neg.html **(LDA 결과 html)** <br>
(2) Ida_result_pos.html **(LDA 결과 html)** <br>
(3) topic_prop_neg.xlsx <br>
(4) topic_prop_pos.xlsx <br>

## 2) setting
코랩에서 코드를 실행하기 전에 다운 받으셔야 할 6개의 파일들입니다. <br>
(1) co_occurrence_matrix.csv <br>
(2) dataset_raw.xlsx (**데이터셋)** <br>
(3) one_char_list.xlsx (**1글자 키워드 리스트)** <br>
(4) remove_app_list.xlsx (**분석 제외 대상 앱 리스트**) <br>
(5) replace_list.xlsx (**단어 치환 리스트)** <br>
(6) stopword_list.xlsx (**불용어 리스트)** <br>

## 3) OKT_colab_crawling.ipynb
해당 파일의 코드를 코랩에 돌리시면 됩니다. <br>
(코드 설명도 함께 해두었습니다.)
