# FlaskObjectDetection - TensorFlow

## Project
- This project is worked with tools tensorflow version 1,
- When you install tensorflow v2, the project is already updated to directly call the tools of version 1
## Run Project
##### Install requirements
```
pip install -r requirements.txt
```
##### Download Model [frozen_inference_graph.pb](https://github.com/datitran/object_detector_app/blob/master/object_detection/ssd_mobilenet_v1_coco_11_06_2017/frozen_inference_graph.pb)
* Create folder ssd_mobilenet_v1_coco_11_06_2017
```
mkdir ssd_mobilenet_v1_coco_11_06_2017
```
* Copy frozen_inference_graph.pb and paste in folder ssd_mobilenet_v1_coco_11_06_2017
##### Run flask
```
flask run
```

[![](images/logo.png)](https://www.tensorflow.org/)

## Using

<p align="center">
  <img src="images/image3.png" width="350"/>
  <img src="images/image4.png" width="350"/>
</p>

<p align="center">
  <img src="images/image5.png" width="350"/>
  <img src="images/image6.png" width="350"/>
</p>

## Tests

<p align="center">
  <img src="tests/fiesta.jpg" width="350"/>
  <img src="uploads/fiesta.jpg" width="350"/>
</p>