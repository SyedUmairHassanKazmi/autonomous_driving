# Autonomous Driving 
Author: Syed Umair Hassan Kazmi

Their are 3 algorithims inside this repositry. 1 to detect vehicles, 1 to detect signs and last one to detect lanes. \
Code to detect vehicle and signs are written in one notebook on colab. They should also be opened on colab for proper view. \
Code to detect lanes are written on local jupyter notebook. They should be opened locally for proper view. 

Videos of results can be downloaded from their respective folders which will give a better sense of the results.

Below are pictures of results of all 3 algorithims.

## Vehicle, Human And Traffic Lights Detection

Yolov5 algorithim with pre-trained Yolov5s weights were used for this purpose.

![vehicle1](/../main/vehicle_and_sign_detection/test_image_vehicle.png)
## Signs Detection

Yolov5 alorigthim was trained on custom dataset imported from kaggle.

![sign1](/../main/vehicle_and_sign_detection/test_image_signs.png)

https://user-images.githubusercontent.com/68387964/148737610-ecb2bab1-d525-4fe7-8859-5a99a3a67be3.mp4

## Lane Detection

Simple functions were written using cv2 to detect lanes. Altough it detects lanes pretty good, \
it works only on straight roads and on some videos only.

![lane1](/../main/lane_detection/out_image.jpeg)


