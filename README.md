

# TensorFlow-Object-Detection
#### This is a slightly modified version of object_detection_tutorial of TensorFlow official documentation but for live object detection.

### The required depenendcies: 
-Python

-TensorFlow

-Tensorboard

-Protobuf v3.4 or above


### To download TensorFlow and TensorFlow GPU you can use pip or conda commands:
#### For CPU
```ruby
pip install tensorflow
```
#### For GPU
```ruby
pip install tensorflow-gpu
```
### Other libraries you'll need: 
```ruby
pip install --user Cython
```
```ruby
pip install --user contextlib2
```
```ruby
pip install --user pillow
```
```ruby
pip install --user lxml
```
```ruby
pip install --user jupyter
```
```ruby
pip install --user matplotlib
```
### Next, we need to install Protobuf: 
###### protocol buffer (Protobuf), usually referred as Protobuf, is a protocol developed by Google to allow serialization and deserialization of structured data. Google developed it with the goal to provide a better way, compared to XML, to make systems communicate.

 You need to Download [Protobuf](https://github.com/protocolbuffers/protobuf/releases) version 3.4 or above and extract it.
 

Now you need to Clone or Download TensorFlow’s Model from [Github](https://github.com/tensorflow/models). Once downloaded and extracted rename the “models-masters” to just “models“.

 Now, keep “models” and “protobuf” under one folder “Tensorflow1“
 
Next, go inside the Tensorflow folder and then inside research folder and run protobuf from there using this command:

```ruby
"path_of_protobuf's bin"./bin/protoc object_detection/protos/
```

Lastly, you'll have to download COCO (Common Objects in Context) dataset, COCO is a large-scale object detection, segmentation, and captioning dataset and that aims to enable future research for object detection, instance segmentation, image captioning, and person keypoints localization. 

First, navigate to models>research>object_detection>g3doc>tf1_detection_zoo.md which contains all the models, choose a model depending on your machine 
[Here's the link](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1_detection_zoo.md)

### Now copy and paste the py file in this repo and paste it in Object_detection folder (within tensorflow1/models/research) and run it. 


 
