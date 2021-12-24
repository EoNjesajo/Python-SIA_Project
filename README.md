# SIA_Project : 인공위성 영상에서 건물 및 도로에 대한 Semantic Segmentation
<img width="601" alt="평가지표" src="https://user-images.githubusercontent.com/90492809/147353904-0b195d0d-ff2a-4c37-8f8e-dcddaafe67c6.png">

## Team
수업 중 랜덤으로 편성
- 김원겸
- 홍성민
- 박태원
- 이제혁
## 기간
2021.11.8 ~ 2021.12.5

# 프로젝트 중 수행한 역할
## 데이터탐색
- Json으로 제공된 라벨에 대한 특성 분석
- Json의 특성을 활용하여 PNG로 된 라벨 생성하는 함수 구현
- 동시검출을 위한 정보 파악 

## 데이터준비
- 동시검출을 위한 라벨 생성 함수 구현
- 데이터셋 함수 구성
- 성능향상을 위한 n분할 이미지 생성(대략 10% 성능향상)

## 모델선택훈련
- 최적의 모델과 인코더, Activation을 테스트하기 위한 함수 구현

## 결과 시각화
- 최종 mIoU : 0.8351
