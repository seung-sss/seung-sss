## About Me

Computer Vision 분야를 중심으로 AI를 공부하고 있는 신승혁입니다.
AI Engineering과 Data Engineering에 흥미를 갖고 공부를 이어가고 있습니다.

기업과 고객의 관점을 이해하고, 이를 토대로 AI 기술을 통해 문제를 해결하고 서비스를 만들어 낼 수 있는 개발자가 되고 싶습니다.
최종적으로는 이러한 경험을 토대로 문제 정의부터 Product Serving까지 모든 파이프라인을 아우를 수 있는 Problem Solver로 성장하고 싶습니다.

[자기소개 더 보기](https://www.notion.so/62660361b3144cc0b85a772d8a2cc3fa)

- 인하대학교 경영대학 경영학과 & 공과대학 소프트웨어융합공학 학사
- Naver Connect Boostcamp AI Tech 2nd. 

<br>

## Skills & Projects

<br>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Pytorch-EE4C2C?style=flat-square&logo=Pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/-Tensorflow-FF6F00?style=flat-square&logo=Tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white"/>

### [올바른 손 씻기 교육을 위한 손 씻기 단계 인식 모델](https://github.com/boostcampaitech2/final-project-level3-cv-04)
- 개요	
	- 정부 권장 손 씻기 6단계를 실시간으로 탐지하는 모델을 제작하고 웹을 통해 배포하는 프로젝트 입니다.
- 역할	
	- Video 데이터를 효율적으로 처리하기 위한 방법을 고민하고, 이를 토대로 Video Classification 모델(X3D)을 연구하였습니다.
	- 신뢰도 높은 Validation 데이터셋을 확보하기 위해 자체적으로 데이터셋을 제작하였습니다. 
	- Pseudo Labeling 및 손 영역 탐지를 위해 Pretrained Hand Detection 모델을 탐색 및 실험하였습니다.
	- Object Detection 모델(YOLOv5)을 연구하였습니다. 

<br>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Pytorch-EE4C2C?style=flat-square&logo=Pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white"/> <img src="https://img.shields.io/badge/WandB-FFBE00?style=flat-square&logo=Weights&Biases&logoColor=white"/> <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=PostgreSQL&logoColor=white"/>

### [모델 경량화](https://github.com/seung-sss/model-optimization-level3-cv-04)
- 개요
	- Edge-Device에 탑재될 정도로 가벼운 AI 모델을 개발하는 프로젝트 입니다.
- 역할
	- 경량 모델 탐색 및 AutoML을 활용한 최적 모델 탐색을 진행하였습니다.
	- DB 연동을 통해 실험 결과를 효율적으로 저장하고, 이를 기반으로 여러 GPU에서 병렬적으로 모델 탐색이 진행될 수 있도록 하였습니다.
	- AutoML을 통한 모델 탐색 과정에서 데이터 캐싱을 통해 멀티 프로세싱이 가능하도록 구현하였습니다.

<br>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Pytorch-EE4C2C?style=flat-square&logo=Pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white"/> <img src="https://img.shields.io/badge/WandB-FFBE00?style=flat-square&logo=Weights&Biases&logoColor=white"/>

### [눈바디 AI Challenge: Semantic Segmentation](https://github.com/seung-sss/alchera-ai-challenge) (4th place out of 00 teams)
- 개요
	- 촬영된 사람 사진에서 사람의 몸을 각 신체부위 별로 분류하는 Semantic Segmentation AI 모델을 개발하는 프로젝트 입니다.
- 역할
	- EDA를 통한 데이터 전처리를 진행하였습니다.
	- Semantic Segmentation 모델(DeepLabV3+)을 연구하였습니다.

### [재활용 쓰레기 탐지: Semantic Segmentation](https://github.com/seung-sss/semantic-segmentation-level2-cv-04) (3rd place out of 18 teams)
- 개요
	- 촬영된 쓰레기 사진에서 픽셀 단위로 재활용 품목을 분류하는 Semantic Segmentation AI 모델을 개발하는 프로젝트 입니다.
- 역할
	- Pytorch 기반의 베이스라인을 설계 및 구축하였습니다.
	- EDA를 통한 데이터 전처리를 진행하였습니다.
	- Semantic Segmentation 모델(FCN, UNet++, DeepLabV3, DeepLabV3+)을 연구하였습니다.
	- TTA & Ensemble(Soft Voting) 코드를 구현하였습니다.

### [재활용 쓰레기 탐지: Object Detection](https://github.com/seung-sss/object-detection-level2-cv-04) (3rd place out of 18 teams)
- 개요
	- 촬영된 쓰레기 사진에서 픽셀 단위로 재활용 품목을 분류하는 Semantic Segmentation AI 모델을 개발하는 프로젝트 입니다.
- 역할
	- MMDetection & YOLOv5를 활용하여 실험 환경을 구축하였습니다.
	- EDA를 통한 데이터 전처리를 진행하였습니다.
	- Object Detection 모델(YOLOv5-m, Faster R-CNN, Cascade R-CNN)을 연구하였습니다.

### [마스크 착용 상태 분류: Image Classification](https://github.com/seung-sss/image-classification-level1-24)
- 개요
	- 촬영된 사람 얼굴 사진에서 마스크 착용 상태 및 성별, 연령대를 분류하는 AI 모델을 개발하는 프로젝트 입니다.
- 역할
	- Darknet53 모델을 직접 구현해 보았습니다.
	- EDA를 통한 데이터 전처리를 진행하였습니다.
	- Image Clssification 모델(ResNet18, EfficientNet-b7)을 연구하였습니다.
	- 모델 성능 향상을 위한 Cutmix를 코드로 구현하였습니다.
 
<br>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/GUI-41CD52?style=flat-square&logo=Qt&logoColor=white"/> 

### [주식 분석 프로그램](https://github.com/seung-sss/image-classification-level1-24)
- 개요
	- 실시간 주가 정보 및 주가 데이터를 통한 주식 분석 결과, 이용자 맞춤형 주식 종목 추천 기능을 제공하는 프로그램을 개발하는 개인 프로젝트 입니다.
- 역할
	- PyQt를 통해 UI를 설계 및 제작하였습니다.
	- 라이브러리와 웹 크롤링을 통해 데이터를 수집하였습니다.
	- 주식 분석 알고리즘을 설계 및 구현하였습니다.
	- 이용자 선호 지표에 따른 종목 추천 기능을 구현하였습니다. 

<br>

## Contact Me

- sjun804@gmail.com