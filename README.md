# 데이콘 포디블록 구조 추출 AI 경진대회
2D 이미지 기반 블록 구조 추출 AI 모델 개발
</br></br>

## Purpose
2D 이미지 내 포디블록의 10가지의 블록 패턴들의 존재 여부를 분류하는 Multi-Label Classification
</br></br>

## Model
EfficientNet_B0
</br></br>

## Data
실험 환경에서 촬영된 학습 데이터(3D 모델링 추정)  
실제 환경에서 촬영된 테스트 데이터
</br></br>

## Process
- Background Removal
- Compose new Backgound
- Augmentation
- Multi-label KFOLD
</br></br>

## Result
||Public|Private|
|---|---|---|
|Score|0.93196|0.92612|
|Place|67th|68th|
