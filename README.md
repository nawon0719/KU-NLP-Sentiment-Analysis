# KU-NLP-Sentiment-Analysis

### 0. 실행 환경
- Google colab 에서 진행
- 런타임 유형 하드웨어 가속기 : GPU

<br>

### 1. Korean Sentiment Analysis
- `Korean_Sentiment_Analysis_Submission.ipynb`  
KoELECTRA base v3 모델 사용

<b>실행 방법</b>  
KOR.zip을 압축해제하여 모두 파일 업로드

각 셀을 실행하며 진행

데이터로드 : https://github.com/e9t/nsmc.git

맞춤법검사는 실시간으로 진행할 수 있지만, 시간효율상 이미 완료된 버전 로드 가능 (KOR.zip 내의 train_spell.csv). 파일 로드시에는 맞춤법검사 진행하지 않아도 무방

<br>

<b>코드 참고</b>

hanspell 코드 참고 : https://github.com/ssut/py-hanspell

koElectra 코드 활용 : https://github.com/monologg/KoELECTRA

전체적인 모델링 코드 및 학습내용 참고 : 

1) https://mccormickml.com/2019/07/22/BERT-fine-tuning/

2) https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP

<br>

### 2. English Sentiment Analysis
- `English_Sentiment_Analysis_Submission.ipynb`  
ELECTRA base 모델 사용

<b>실행 방법</b>  
ENG.zip을 압축해제하여 모두 파일 업로드

각 셀을 실행하며 진행

맞춤법검사는 실시간으로 진행할 수 있지만, 시간효율상 이미 완료된 버전 로드 가능 (ENG.zip 내의 friends_train_spell_done.csv). 파일 로드시에는 맞춤법검사 진행하지 않아도 무방

<br>

<b>코드 참고</b>

Spell Checker : https://pypi.org/project/language-tool-python/

전체적인 모델링 코드 및 학습내용 참고 : 

1) https://mccormickml.com/2019/07/22/BERT-fine-tuning/

2) https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP
