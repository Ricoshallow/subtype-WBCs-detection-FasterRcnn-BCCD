# Training a TensorFlow Faster R-CNN Object Detection Model on enhanced BCCD

## Introduciton
 Two-stage object detection model Faster-rcnn were applied to classify 
 
 **neutrophils, eosinophils, monocytes, and lymphocytes** on an enhanced BCCD dataset.

## Preparing  Images and Annotations

 BCCD image is avaliable on https://www.kaggle.com/paultimothymooney/blood-cells

 Image annotation can accomplish by **labelImg**  <https://github.com-/tzutalin/labelImg>

## Creating TFRecords and Label Maps
 Transform your annotation file to ```.tfrecord``` file. 

## Training the model on GoogleColab 
 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15-zp5lGQhg03lTV10lVd6oMW3DuZTlAM?usp=sharing)