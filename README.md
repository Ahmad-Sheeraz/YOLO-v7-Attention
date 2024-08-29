# Attention based YOLOv7 for Gastric Lesion Detection (Master's project)

*YOLOv7 & SE Attention Module Integration*

-We developed an automated gastric lesion detector using an enhanced YOLO-v7 object detection algorithm for effectively identifying gastric lesions, including non-cancerous, pre-cancerous, and cancerous cases.
-By integrating the Squeeze and Excitation attention module into the network’s backbone architecture, we substantially enhance the identification of small-sized lesions. 


## Data

Dataset: Used private dataset total amount of around 60k samples. The classes included Cancer, Adenoma, Ulcer and Normal cases. 

<p align="center">
<img src="https://github.com/Ahmad-Sheeraz/YOLO-v7-Attention/assets/dataset.png" width="550" alt="dataset"/>
</p>

## Architecture
The architecture is based on YOLOv7 with the modification in the backbone architecture by intergrating Squeeze & Excitation attention module.

<p align="center">
<img src="https://github.com/Ahmad-Sheeraz/YOLO-v7-Attention/assets/yolov7_architecture.png" width="550" alt="dataset"/>
</p>

<p align="center">
<img src="https://github.com/Ahmad-Sheeraz/YOLO-v7-Attention/assets/dataset/se_architecture.png" width="550" alt="dataset"/>
</p>



## Training
Training stratigies are mentioned in the Research article.


## Results

<p align="center">
<img src="https://github.com/Ahmad-Sheeraz/YOLO-v7-Attention/assets/results.png" width="550" alt="results"/>
</p>

### Predictions-

<p align="center">
<img src="https://github.com/Ahmad-Sheeraz/YOLO-v7-Attention/assets/det1.png" width="550" alt="Training plot"/>
</p>
<p align="center">
<img src="https://github.com/Ahmad-Sheeraz/YOLO-v7-Attention/assets/det2.png" width="550" alt="Training plot"/>
</p>

## Code

The modification in the code has been done in the original YOLOv7 repository.
