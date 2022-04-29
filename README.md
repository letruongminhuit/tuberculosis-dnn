# Automated Evaluation of Tuberculosis Using Deep Neural Networks

Here is our implementation of approach built for the paper named: Automated Evaluation of Tuberculosis Using Deep Neural Networks

# Introduction 

Tuberculosis (TB) is a chronic, progressive infection that often has a latent period after the initial infection period. Early awareness from those period to have better prevention steps becomes an indispensable part for patients who want to lengthen their lives. Hence, applying cutting-edge technologies to support the medical business domain plays a key role in improving speed and accuracy in methods of diagnosis. Deep Neural Network-based technique (DNN) is one of such methods which offers positive results by leveraging the advantages of analyzing deeply the data, especially image data format via tons of deep layers of the neural networks. Our study was wrapped up by objectively assessing the performance of modern Deep Neural Network approaches and suggesting a model offering good results in terms of the selected metrics as defined later. In order to achieve optimized results, the chosen model must adapt well to the datasets but require less hardware and computational resources.

# Datasets 
We used 4 datasets: 
* Tuberculosis (TB) Chest X-ray
* Shenzhen Chest X-ray
* Montgomery Chest X-ray
* India Chest X-ray

# Requirements
* Tensorflow 2.5
* Keras

# Results

Here are the distributions of the expected results achieved from our models after training and testing phases: 

![Hinh5-1](https://user-images.githubusercontent.com/41055526/165943464-4bf64339-0866-455e-b7b8-8ce39de52bd9.png)

_Confusion  matrices  for  models  applying  to Tuberculosis (TB) Chest X-ray database - MobileNet-V3 showsbetter results with True Positive and False Negative images detected are quite high - 64 and 62 correspondingly_

![Hinh5-2](https://user-images.githubusercontent.com/41055526/165943475-5826e50e-c923-442c-94d3-a69f4ac0f3d9.png)

_Confusion matrices for models applying to ShenzhenChest X-ray Set - MobileNet-V3 provides the second good resultswith True Positive and False Negative images detected are high- 4 and 13 correspondingly_

![Hinh5-3](https://user-images.githubusercontent.com/41055526/165943486-120de360-e96b-4c5e-9381-7c501e5fb03c.png)

_Confusion  matrices  for  models  applying  to Montgomery Chest X-ray Set - MobileNetV3 provides the betterresults with True Positive and False Negative images detectedare high - 7.5 and 12 correspondingly_

![Hinh5-4](https://user-images.githubusercontent.com/41055526/165943497-e8c59354-6c3c-4153-9094-312562b7f8c9.png)

_Confusion matrices for models applying to India ChestX-ray Set - MobileNet-V3 reveals the good results with TruePositive and False Negative images detected are high - 12 and10 correspondingly_

Here are the final results of our papers: 

![image](https://user-images.githubusercontent.com/41055526/165944205-b51e3499-8b6d-4a59-8fcc-2648818ed7f7.png)


If this paper is helpful with you, please cite us with these details: 

> `Le, T.-M., Nguyen-Tat, B.-T., & Ngo, V. M. (2022). Automated evaluation of Tuberculosis using Deep Neural Networks. EAI Endorsed Transactions on Industrial Networks and Intelligent Systems, 9(30), e4. https://doi.org/10.4108/eetinis.v8i30.478`
