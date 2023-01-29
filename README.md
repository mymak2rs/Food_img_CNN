# 음식 사진으로 어떤 음식인지 구분해내는 CNN 모델을 개발 하는 것을 목표로 함
-----
* Dataset은 Google 에서 직접 수집한 20종류, 2921장의 음식 이미지(jpg포맷)이다.

* 훈련 데이터와 검증 데이터로 구분하여 분류

* Data augmentation 수행

* CNN 모델 설계

* Optimizer는 Adam을 이용했고, learning rate는 adam의 기본값인 0.001, loss_function = categorical_crossentropy로 학습 진행

* checkpoint를 사용하여 training과 test에서 최적의 accuracy를 보이는 모델을 고르고자 함

* 콜백 함수로 ReduceLROnPlateau를 이용

* matplotlib을 통한 accuracy와 loss 확인
-----
## [대표 이미지](#대표-이미지)
![image](https://user-images.githubusercontent.com/116767717/215314387-2c6388aa-57b3-4950-aa83-d4f90936363a.png)
