# Brain Tumor Image-Segmentation
The Tumor Segmentation Dataset is designed specifically for the TumorSeg Computer Vision Project, which focuses on Semantic Segmentation. The project aims to identify tumor regions accurately within Medical Images using advanced techniques.

we use YOLOv8 to Image-Segmentation and dectect the Segmentation is Tumor or Non-Tumor

## Install
* python = 3.9

* numpy = 1.26.3
  
* pytorch = 2.3.0

* matplotlib = 3.9.4

* ultralytics=8.3.51

1.
the env is use pytorch, so need to creat a new enviroment

```
conda env create --file environment.yaml --name <name>
```

if you want to use Yolov8 you need to install ultralytics, and the environment.yaml already have ultralytics

```
pip install ultralytics
```

## Usage
Firsr, the origin dataset is COCO format(save as jaso), we change the COCO format dataset to YOLO format dataset(save as txt), then do next step

run the yolov8.ipynb

## result

![image](https://github.com/gndd1221/Brain-Tumor-Image-Segmentation/blob/c43e32a0a89187ae01271ab2dd321ee0b6d8bfb6/yolo/runs/detect/train/results.png)

![image](https://github.com/gndd1221/Brain-Tumor-Image-Segmentation/blob/c43e32a0a89187ae01271ab2dd321ee0b6d8bfb6/yolo/runs/detect/train/confusion_matrix.png)

