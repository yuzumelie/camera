이 프로그램은 Flickr API를 활용해 Sony, Canon, Nikon 브랜드의 이미지를 수집하고, ResNet18을 기반으로 한 딥러닝 모델로 이미지를 분류합니다. 수집된 이미지는 데이터셋으로 구성되며,
PyTorch를 사용해 학습 및 검증이 이루어집니다. 
학습 과정에서 데이터 증강과 전처리를 통해 모델 성능을 향상시켰습니다. 최종적으로, 정확도와 F1 점수를 사용해 모델의 분류 성능을 평가합니다.