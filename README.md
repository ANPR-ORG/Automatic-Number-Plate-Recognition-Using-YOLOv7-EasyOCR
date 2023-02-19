# Automatic Number Plate Recognition (ANPR)

### Description

The automatic number plate recognition (ANPR) system reads and recognises vehicle number plates using computer vision and image processing methods. A popular object detection model in computer vision problems is YOLOv7. Python software called EasyOCR has optical character recognition (OCR) capabilities.

Use these procedures to perform an ANPR using YOLOv7 and EasyOCR:

* Accumulate a collection of photos showing licence plates for vehicles.
* The dataset can be used to train the YOLOv7 model to recognise licence plates in the photos.
* Use EasyOCR to extract the characters from the number plates that YOLOv7 has detected.
* Extract the licence plate number by using a character recognition algorithm to identify the characters.

A combination of computer vision, machine learning, and image processing methods are needed to solve the difficult problem of ANPR. The numerous variables involved must be carefully tuned and optimised. But, you may create a reliable and accurate ANPR system utilising YOLOv7 and EasyOCR.
<div align="center">
    <a href="./">
        <img src="./figure/performance.png" width="79%"/>
    </a>
</div>

## Training
### Clone Repository
```shell
git clone https://github.com/ANPR-ORG/ANPR-using-YOLOV7-EasyOCR.git
pip install -r requirements.txt
```


## Trained Model
[`best.pt`](https://drive.google.com/file/d/1muS4VhL72di10Ob8-mHLmTz2cLDdz9Ug/view?usp=share_link)
