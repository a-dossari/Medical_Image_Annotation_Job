# Medical Image Annotation Job

### **Project Overview**
The goal is to build a product that helps doctors quickly identify cases of pneumonia in children. 

As such, this project is designed to test your ability to build a labeled dataset that distinguishes between healthy and pneumonia x-ray images; this can be used by ML engineers later on down the line to build a classification product. Your main task will be to create a data labeling job using [Appen's platform](https://client.appen.com/jobs)

This project is designed to build a labeled dataset that distinguishes between healthy and pneumonia x-ray images; this can be used by ML engineers later on down the line to build a classification product.


### **The Data**
This dataset is a modified version of [Kaggle chest x-ray dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia), with most labels removed. Every piece of data is a chest x-ray image. You may see images taken that are slightly different in size and taken under slightly different exposure times. A typical, labeled image is shown below.

![alt text](https://video.udacity-data.com/topher/2019/April/5cae622b_annotated-chest-xray/annotated-chest-xray.png) 
<p align="center">
    A labeled, healthy, chest x-ray image. Pay close attention to the two lungs and diaphragm (below the lungs)
</p>



#### What Does Pneumonia Look Like?
This is a challenging task because it is not always clear when pneumonia symptoms are present or not in an image. As such, your system is not meant to be a replacement for a doctor, only to aid in quickly identifying healthy patients and surfacing potential cases of pneumonia.

There are a few different visual symptoms that indicate pneumonia. The most important areas to have annotators pay attention to are the lungs and the diaphragm.

* A normal, healthy image will depict clear lungs without any areas of abnormal cloudiness/opacity; there may be structured, web-like vasculature in the lungs but otherwise that area should be clear. In healthy images, you are also more likely to see a diaphragm shadow.
* A pneumonia image may include a few things: areas of cloudiness/opacity in several concentrated areas or one large area. You may also see a general pattern of opacity that obscures the structure of the lungs, heart, and diaphragm.

![alt text](https://video.udacity-data.com/topher/2019/April/5cae62e6_healthy-example/healthy-example.png)
<p align="center">
    Some characteristics of a healthy image: a clear lung area
</p>

![alt text](https://video.udacity-data.com/topher/2019/April/5cae6304_pneumonia-examples/pneumonia-examples.png)
<p align="center"> 
Examples of pneumonia symptoms: (Left) a concentrated, opaque area in the lungs, (Right) multiple, smaller opaque areas throughout the lung area and any diaphragm shadow is obscured 
</p>


### **Inspiration**
* Can help flag serious cases
* Quickly identify healthy cases
* And, generally, act as a diagnostic aid for doctors
