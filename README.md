# Comma


### Goal

Deliver reproducible trained models with enough validation for an autonomous vehicle by using environment simulator (**Carla**), ML and Computer vision algos and/or simultaneous localization and mapping. 

### Introduction

An autonomous vehicle or self-driving car is a vehicle that must be able to navigate without human input or a pre-established destination over a path. It makes its own decisions and it is able to cope with all of the situations continuously by making environmental decisions over time. An agent will perform some tasks like driving from point A to B based on a set of parameters. It will be rewarded in a positive or negative way depending on its actions. 

### Objectives / Deliverables

- **Vehicles classification** [Jupyter notebook](https://github.com/pepsm/Comma/VehiclesClassification.ipynb) 
- **Traffic Signs classification** 
- **Car detection** [Carla](https://github.com/affinis-lab/car-detection-module)
- **Lane detection**
- **Enviroment segmentation** [U-Net](https://github.com/henyau/Image-Segmentation-with-Unet)
- **Traffic Sign Detection** 
- **Reinforcement learning** [[idea]](https://github.com/carla-simulator/reinforcement-learning)
 
### Image Recognition problems

  - **Classification** It is the identification of the “class”, i.e. the category to which an image belongs. An image can have only one class.  
  - **Tagging** It is also a classification task but with a higher degree of accuracy. It can recognize the presence of several concepts or objects within an image.   One or more tags can therefore be assigned to a particular image.  
  - **Detection** This is necessary when you want to locate an object in an image. Once the object is located, a bounding box is placed around the object in question. 
  - **Segmentation** This is also a detection task. Segmentation can locate an element on an image to the nearest pixel. For some cases, it is necessary to be extremely precise, as for the development of autonomous cars. [[dataset]](https://github.com/DanielHfnr/Carla-Object-Detection-Dataset)

 
 **Datasets :** 
 [[TU Simple]](https://paperswithcode.com/dataset/tusimple), [[CULane]](https://paperswithcode.com/dataset/culane)

