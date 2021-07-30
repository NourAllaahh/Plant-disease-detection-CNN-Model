# Plant-disease-detection-CNN-Model

A CNN Model used to scan plants to detect diseases, this Model is integrated in E-Farming mobile application and here are screenshots of the function used by this model inside the application:

<img src="https://user-images.githubusercontent.com/72973609/127567307-475f68ee-54f2-44d6-91b5-2a4d34b72c0e.jpg" alt="alt text" width="200" height="400"> <img src="https://user-images.githubusercontent.com/72973609/127567536-701867ec-d1ea-4f52-bef3-e57e81c1e9b4.jpg" alt="alt text" width="200" height="400"> <img src="https://user-images.githubusercontent.com/72973609/127567765-268f55d3-edbb-4693-a7c6-4dc871ebb297.jpg" alt="alt text" width="200" height="400">

## Methodolgy 

Data Gathering:
* For Plant disease detection
we used a publicly available and famous Dataset [“Plant Village Dataset”](https://www.kaggle.com/emmarex/plantdisease)
This Dataset Contains 54,305 images of plant leaves collected under different environment Conditions
Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, and Tomato. 
We Decided to focus on Tomato and potato classes, Here are the generate Dataset Classes
<img src="https://user-images.githubusercontent.com/72973609/127651065-7fe7ab9f-fc89-4e66-8e48-adf43dbc6571.png" alt="alt text" width="300" height="200">


## Techniques:

Convolutional Neural Network: is a class of deep neural networks, most applied to analyzing visual imagery. its widely used in applications of image and video recognition.

<img src="https://user-images.githubusercontent.com/72973609/127575041-c73b3e28-9510-465d-8c8b-7ac991f5546e.png" alt="alt text" width="500" height="200">

## Creation and Compilation

* Pre-process The Images is an improvement of the image data that suppress undesired distortions or enhances some image features important for further processing.

<img src="https://user-images.githubusercontent.com/72973609/127650761-1268c6b2-1149-4585-bda1-35b46a86808c.png" alt="alt text" width="400" height="300">

* Build Convolutional Neural Network with Type of layers (Conv2D, MaxPooling2D, Flatten, Dense….) 
<img src="https://user-images.githubusercontent.com/72973609/127650435-c7420629-5ff5-4e35-8e88-8be350bfeaac.png" alt="alt text" width="400" height="300">


* Sample of Input after Convolution Layer 
<img src="https://user-images.githubusercontent.com/72973609/127650694-683284fa-67a7-478f-9a05-6205862cd429.png" alt="alt text" width="400" height="300">

* Sample of Input after Max Pooling Layer

<img src="https://user-images.githubusercontent.com/72973609/127661725-9e214906-a95c-4261-8c6b-55c59f16f4f6.png" alt="alt text" width="400" height="300">

* Train The Model results and got accuracy 0.9592

<img src="https://user-images.githubusercontent.com/72973609/127650706-67c85d9d-bd6d-4eef-8e56-f8381a95b631.png" alt="alt text" width="400" height="300">

* Plot Graphs for Training Accuracy and Training Loss

<img src="https://user-images.githubusercontent.com/72973609/127650719-9145a664-28d9-414f-8377-ec8b9cc1448b.png" alt="alt text" width="200" height="200"> <img src="https://user-images.githubusercontent.com/72973609/127650729-064ab382-8b05-4b5b-8aa3-0b84022efcf0.png" alt="alt text" width="200" height="200">

