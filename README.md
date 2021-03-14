# Bicycle-Helmet-Wearing-Detection

### Overview
After creating a tensorflow lite model that continuously performs bicycle helmet detection using quantized [MobileNet SSD](https://github.com/tensorflow/models/tree/master/research/object_detection) and [Bicycle Helmet Dataset](https://www.kaggle.com/andrewmvd/helmet-detection), it was made to be used in real time on Android by referring to TensorFlow Lite Object Detection Android Demo.
## Usuage
All models and data are ready. To run, download this repository, open it using Android Studio, and run it with an emulator or personal device.

## Model Training
### Dataset
After downloading the data set from kaggel, updating it on roboflow, visualizing the data, checking basic information, and dividing it into train, validation and test data at ratio of 70%, 20% and 10%.
![image](https://user-images.githubusercontent.com/30094719/111058555-c3541c00-84d2-11eb-94c1-6eacf469b504.png)
### Training 
check [Roboflow-TFLite-Object-Detection.ipynb](https://github.com/BEOKS/Bicycle-Helmet-Wearing-Detection/blob/main/Roboflow-TFLite-Object-Detection.ipynb) file, The file is very complex, so I recommend viewing it in colab. 

### Test
As a result of learning, you can see the result that distinguishes between wearing a helmet and not wearing it. You can check out the demo video through the link below.<br>

![image](https://user-images.githubusercontent.com/30094719/111058817-678a9280-84d4-11eb-820a-94e930bdf538.png)
![image](https://user-images.githubusercontent.com/30094719/111058821-7113fa80-84d4-11eb-9d01-ee3f88337ca7.png)
<br>
Video : https://user-images.githubusercontent.com/30094719/111058799-4a55c400-84d4-11eb-87f0-0948fcc11ff0.mp4


## Reference
1. TensorFlow Lite Object Detection Android Demo,https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/android
2. How to Train a Custom TensorFlow Lite Object Detection Model, https://blog.roboflow.com/how-to-train-a-tensorflow-lite-object-detection-model/
3. Bicycle Helmet Dataset, https://www.kaggle.com/andrewmvd/helmet-detection
4. MobileNet SSD, https://github.com/tensorflow/models/tree/master/research/object_detection
