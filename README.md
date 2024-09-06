# A Lightweight Insulator Defect Detection Model Based on Drone Images

## Introduction
This is our PyTorch implementation of the paper "[`A Lightweight Insulator Defect Detection Model Based on Drone Images`](https://doi.org/10.3390/drones8090431)" published in ***Drones***.


## <div align="left">Quick Start Examples</div>

<details open>
<summary>Install</summary>

First, clone the project and configure the environment.
[**Python>=3.7.0**](https://www.python.org/), [**PyTorch>=1.7**](https://pytorch.org/get-started/locally/).

```bash
git clone https://github.com/LuYang-2023/Insulator-defect-detection.git  # clone
cd Insulator-defect-detection
pip install -r requirements.txt  # install
```
</details>

<details open>
<summary>Train</summary>



```python
python train.py --cfg models/LiteYOLO-ID.yaml --data data/mydata.yaml
```
</details>


<details>
<summary>Test</summary>


```bash
python val.py --data data/mydata.yaml --weights best.pt --task test
```
</details>


## 1.IDD-YOLO architecture diagram
<div align="center">
    <img src="IDD_YOLO.png" width="1000" alt="IDD-YOLO">
</div>

## 2.LCSA attention mechanism

<div align="center">
    <img src="LCSA_attention_mechanism.png" width="1000" alt="LCSA_attention_mechanism">
</div>


## 3.Dataset
My dataset contains sensitive information from the Tianjin Power Grid Company, and I need to communicate with them first to confirm whether this data can be made public.


## 4.Experiment


**4.1 Edge Platform Deployment**


![](Jetson_TX2_NX_EX.png)

## 5 Insulator defect detection results


![](IDD-YOLO_detection_results.png)

## Author's Contact
Email：yj20220275@stud.tjut.edu.cn



