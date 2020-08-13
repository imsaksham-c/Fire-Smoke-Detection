# Fire-Smoke-Detection
Detecting Fire, Smoke using Computer Vision, Open CV and PyTorch

Early fire/smoke detection plays a very important role in protecting many lives also property loss can be reduced and downtime for the operation minimized through early detection. Therefore in this project I have developed an Computer Vision & Deep Learning pipeline for fire and smoke detection.

### Demo Output - 
![](https://github.com/imsaksham-c/Fire-Smoke-Detection/blob/master/utils/demo.gif)

### Download the Dataset - [download](https://github.com/DeepQuestAI/Fire-Smoke-Dataset/releases/download/v1/FIRE-SMOKE-DATASET.zip)

### Dataset Folder - 
    Train
        - Fire
        - Neutral
        - Smoke       
    Test
        - Fire
        - Neutral
        - Smoke
        
    Dataset contains 1000 images of each class
    
### Model Structure -
For traing the model I have used transfer learning technique. Architecture used here is ResNet50 which is pretrained on ImageNet dataset.
I have achieved validation accuracy of 93% using ResNet.
For more info about training and graphs - open Training.ipynb

![Training Loss](https://github.com/imsaksham-c/Fire-Smoke-Detection/blob/master/utils/trainloss.png)

![Model Accuracy](https://github.com/imsaksham-c/Fire-Smoke-Detection/blob/master/utils/accuracy.png)

### Sample Results
![](https://github.com/imsaksham-c/Fire-Smoke-Detection/blob/master/utils/fire.png)
![](https://github.com/imsaksham-c/Fire-Smoke-Detection/blob/master/utils/smoke.png)
![](https://github.com/imsaksham-c/Fire-Smoke-Detection/blob/master/utils/neutral.png)
    
### Steps - 
1. Clone/Download the repo
2. Download the dataset
3. For training - open Training.ipnb
4. For inference - open Inference.ipynb

### Requirements - 
Python3

PyTorch

OpenCV

Matplotlib

Numpy

### Upcoming Work - 
RestAPI (rest api using flask)

### References
1. PyImageSearch - https://www.pyimagesearch.com/2019/11/18/fire-and-smoke-detection-with-keras-and-deep-learning/
2. DeepQuestAI/Fire-Smoke-Dataset - https://github.com/DeepQuestAI/Fire-Smoke-Dataset
