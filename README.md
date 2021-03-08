# Augmentation
A repository for image augmentation


## 1. Simple Copy-Paste is a Strong Data Augmentation Method for Instance Segmentation

Jittering => standard scale 있고 large scale 있음.

Self-training Copy-paste 사용해서 하게 됨.

이게 뭐냐면 세그멘테이션 라벨링 된 이미지를 Copy-Paste Augmentation 해서 모델 하나를 supervised learning 함.

라벨링 되지 않은 이미지에 대해 psuedo labels를 생성함.

ground-truth instances를 위에 생성한 psuedo labels 과 미리 라벨링 된 supervised labeled images에 복사해 모델을 새로운 data에 학습시킴.
