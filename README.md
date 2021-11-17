# Brain_tumor_Classification
Tensorflow와 Keras를 활용한 뇌종양 식별기   
### Dataset
https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection  <br>

### Yes  <----------------------------------------->     No
![eyseyesyse](https://user-images.githubusercontent.com/55770741/141991389-40f8e4cc-8ade-41f2-b464-d674dcb8a4fd.JPG)
![no](https://user-images.githubusercontent.com/55770741/141990961-d4458a35-21ae-49ff-b7f3-e14b997ebfba.JPG)<br><br>

## Model 구조
1. Conv - BN - ReLU - Max  
2. Conv - BN - ReLU - Max  
3. Conv - BN - ReLU - Max  
4. Flatten - Dense - Dropout - Sigmoid  

## Accuracy
||acc|val_acc|loss|val_loss|  
|---|---|---|---|---|
|1차 시도|86%|84%|32%|33%|
|2차 시도|96%|96%|12%|13%|

# Review
기본적은 CNN의 Model을 여러가지 형태로 변형시켜 Test를 해보았지만, 성능이 쉽게 좋아지지는 않았다. 때로는 간결하고 정교한 Model이 성능이 더욱 잘 나올때가 많다. 이러한 어려움들 속에서 나만의 학습 레이어를 만들어가며 성능을 테스팅하는것이 내가 딥러닝을 하는 이유이자, 흥미로운 부분이다.

# Requirement
+ Python
+ Tensorflow
+ Keras
+ Pandas
+ Numpy
+ Opencv
