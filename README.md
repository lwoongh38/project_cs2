# Text 데이터 광고 필터링을 위한 분류 모델 구축


### abstract
본 프로젝트는 시계열(text) 데이터를 분석하기 위한 전처리 과정에서 사용자가 원하지 않는 정보를 자동적으로 필터링하여 전처리 진행 속도를 상승시키는 것을 목적으로 합니다.
Hate speech 분류에 사용되는 BiLSTM, CharCNN 등의 알고리즘을 활용 가능한지 파악하고 이를 차용하여 인스타그램의 텍스트 데이터에서 광고를 분류하는데 적용하고 각 모델의 성능을 비교하는 프로젝트입니다.

### turorial
본 프로젝트는 jupyter notebook으로 구현될 수 있도록 작성되어 있습니다.  
데이터셋은 data 폴더 안에 레이블별로 나뉘어있습니다.  
data_preprocessing 에 데이터 크롤링부터 전처리에 관한 코드가 작성되어있습니다.
KOBERT, BiLSTM 파일은 각 모델에 대한 코드가 정리되어있습니다.
requirements.txt를 설치하면 오류없이 노트북이 실행되는 것을 확인했습니다.






### 참고문헌

-BEEP! Korean Corpus of Online News Comments for Toxic Speech Detection  
https://paperswithcode.com/paper/beep-korean-corpus-of-online-news-comments 

-한국어 악성댓글 탐지를 위한 댓글 코퍼스 구축기-프로젝트 예제  
https://inmoonlight.github.io/2020/05/28/Retrospect-of-Constructing-Korean-HateSpeech-Dataset/


-SKTBrain의 kobert github  
https://github.com/SKTBrain/KoBERT

-BiLSTM 참고  
https://wikidocs.net/94748