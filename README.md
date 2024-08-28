# SW-AI-Competition-2023
This is the same project as DACON_segmentation.

## 개요
- 대회명 : DACON SW 중심대학 공동 AI 경진대회
- 작업 기간 : 23.07.03 ~23.07.29
- 팀장 : 정동규
- 개발자명 : 정동규 선주환 우진우 곽연규
- 팀명 : 영대 MZ들
- 소속 : 영남대학교 정보통신공학과

## 상세
- 언어 : Python
- 핵심 라이브러리 : torch, tensorflow, pandas, matplot

## 개발 다이어그램

- 기본적인 U-Net 모델을 이용하여 AI모델 구축
- 학습데이터와 실험데이터의 사진의 크기를 맞추기위해 학습데이터에서 Crop으로 이용 (처음에는 resize를 진행했으나 pixel이 줄어드는 과정에서 손실이 많이 생김을 확인)
- 다양한 전처리 과정을 통하여 학습데이터 다양화 (사진반전, 밝기조절)
- CUDA 설정을 통한 GPU 사용법
