# 🐼 Bamboo Summer Competition - Deep Learning PR

해당 프로젝트는 **2025 Bamboo Summer Kaggle Competition** 딥러닝 이미지 분류 프로젝트입니다.  
Google Colab 환경에서 진행되었으며, PyTorch와 ConvNet-tiny을 backbone으로 활용해 진행하였습니다.  

## ✨ 주요 특징
- Kaggle 제공 데이터셋 기반 이미지 분류
- `convnext_tiny.fb_in22k` 백본 사용
- PyTorch + timm을 통한 전이학습(Transfer Learning)
- Label Encoding 및 이미지 전처리 포함

## 📂 구성
- **PR_Anmoonsik.ipynb** : 메인 실험 및 학습 노트북  
- **train.csv / test.csv** : Kaggle Competition 제공 데이터  (용량이슈)

## 🎯 목표
- 경량 모델부터 최신 아키텍처까지 실험하여 대회 환경에서 최적의 성능을 달성하는 것을 목표로 하였습니다.  
- 사전 학습 가중치가 공개된 모델 중 **ResNet**, **EfficientNet**, **ConvNeXt-Tiny**를 실험하였으며,  
  그 중 **ConvNeXt-Tiny**가 Public Score에서 가장 안정적인 성능을 보여 최종 모델로 채택하였습니다.


## 📊 결과
- Public Score: **0.965**
- Private Score: **0.952**  
- Kaggle 리더보드 기준으로 안정적인 성능을 보였으며,  
  학습과 검증 과정 모두에서 비교적 **일관된 결과** 를 확인할 수 있었습니다. 
- 추가적인 하이퍼파라미터 튜닝 및 백본 변경을 통해  
  성능 향상의 가능성이 있습니다.
