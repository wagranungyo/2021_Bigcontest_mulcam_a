# 2021 빅콘테스트 mulcam_a

### ESG 등급평가
- colab환경에서 작업하였기에 .ipynb파일인 점 양해부탁드립니다. 
- 코드를 실행할 시, 경로 설정을 따로 지정해주셔야 합니다.


1. total 데이터셋.ipynb 파일 실행하면 total_dataset.csv 파일형성
 - 우선 용량상의 문제로 전체 pdf파일을 올리지 않았습니다
 - https://www.ksa.or.kr/ksi/4982/subview.do 에서 지속가능경영보고서 pdf파일을 다운받으실 수 있으며 만들어진 total_dataset.csv 파일을 올리겠습니다.  
 - 총 53개의 기업의 지속가능경영보고서 및 C,D등급이 부족하여 기업에서 발표한 브로슈어를 참고하여 데이터셋을 구축하였습니다. 

2. bert_다중분류.ipynb에 total_dataset.csv파일 경로 지정해주고 파일 실행 
 - 등급 기준은 A+, A, B+, B, C, D 총 5가지 등급으로 분류하였고 등급 분류 기준은 한국기업지배구조원의 등급 조회를 참고하였습니다(http://www.cgs.or.kr/business/esg_tab04.jsp)
 
