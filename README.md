## Jupyter Notebook 저장소
기초적인 AI 코드에 대한 실습이 포함되어 있습니다.
### 사용하기
- batchfile_exec_juypter 디렉터리의 batch 파일들은 실행 환경에 맞추어 경로 설정이 필요함: 각각 Jupyter notebook 서버를 실행하는 배치 파일과 tensorboard 서버를 실행하는 배치파일이다.
- 다음 경로와 파일들은 레포지토리에서 제외되어 있음
    - 데이터: Kaggle에서 가져온 dataset(노트북 / 핸드폰 / 피마 인디언 / 보스턴 집값 등등)
    - 이미지: MNIST 데이터 셋의 DL 모델 시험해보기 위한 폰트 이미지
    - 로그: TensorBoard에 뿌려주기 위해 모델 훈련할 때 생성한 로그 파일
    - font: 궁서체 이미지를 만들기 위한 폰트(malgun.ttf / gungseo.ttc)
    - gungseo_images: 궁서체 글자 이미지 파일
    - non_gungseo_images: 돋움체 글자 이미지 파일
- 서체를 작성하는 코드는 cmalgun.ttf와 gungseo.tt 파일로 코드가 작성함: 해당 파일에 대한 경로도 필요에 따라 변경이 필요.
### 배경 이론
배경 이론에 대한 개략적인 내용은 학습 노트에 정리되어 있고, 보다 전문적인 내용은 현재로써는 추가할 예정 없음.
- ML
- DL
- 회귀 / 판단 / 분류 문제
- DNN / CNN / LSTM