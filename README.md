# Anomaly Detection of Deepfake Audio Based on Real Audio Using Generative Adversarial Network Model
PBL Team SWAMPS


### 1. 개발 배경

딥페이크 오디오(딥보이스) 기술의 발전으로 증가한 딥보이스 기반 보이스피싱 피해를 낮추는 것이 목표이며 대화 내용 기반 보이스피싱 탐지 프로그램에 딥보이스 탐지 기술을 추가한 연구 및 시뮬레이터를 개발한다.  


### 2. 전체 구성

2.1 딥보이스 탐지 : 실제 음성을 Mel-Spectrogram, Scaled-MFCC로 변환하여 구성한 데이터 셋을 Ganomaly/f-AnoGAN 모델에 학습시켜 Anomaly Score로 딥페이크 오디오 적용 여부 판별

2.2 내용 기반 탐지 : 피싱대화/일반대화 음성을 STT로 변환 후 벡터화하여 구성한 데이터 셋을 LSTM 모델에 학습 시켜 이진 분류를 통해 보이스피싱 대화 여부 판별

### 성과

- **IEEE ACCESS 저널 Accept(SCI 논문)** -> https://ieeexplore.ieee.org/abstract/document/10769438
- 2023 졸업 프로젝트 평가회 **Grand Prize (대상 수상)**
- 개인정보 혁신인재 양성 분야 PBL 프로젝트 보고회 **Grand Prize (대상 수상)**

### Brochure
<img width="4608" height="3456" alt="_    (1)" src="https://github.com/user-attachments/assets/8c93e874-2dd3-4148-92c2-9b11d9ef0074" />







### ✌️ 참여 인원

|[송다은](https://github.com/daeun6)|[이나영]()|[김지원]()|
| --- | --- | --- |
|<img width="100" src="https://github.com/GDSC-SWU/2023-AI-ML-study/assets/81478444/21400679-dcc3-4731-9638-d8f717e0bc84"/>|<img width="100" src="https://github.com/daeun6/DeepCaptcha/assets/81478444/f1c138c1-8e9c-4f0c-aea1-27743fa18983"/>|<img width="100" src="https://github.com/daeun6/DeepCaptcha/assets/81478444/80e07910-6790-4f58-bf53-0960134e1777"/>|
