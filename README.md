# YOGL: A Lightweight Insulator Defect Detection Network Based on UAV Remote Sensing Images

**Dear reviewers: The source code and pre-trained model weights will be available upon the acceptance of the paper.   Feel free to raise your questions or difficulties in the implementation.**
## <div align="left">Quick Start Examples</div>

<details open>
<summary>Install</summary>

First, clone the project and configure the environment.
[**Python>=3.7.0**](https://www.python.org/), [**PyTorch>=1.7**](https://pytorch.org/get-started/locally/).

```bash
git clone https://github.com/LuYang-2023/ICMA2024.git  # clone
cd ICMA2024
pip install -r requirements.txt  # install
```
</details>

<details open>
<summary>Train</summary>



```python
python train.py --cfg models/IDD-yolov5.yaml --data data/mydata.yaml
```
</details>


<details>
<summary>Test</summary>


```bash
python val.py --data data/mydata.yaml --weights best.pt --task test
```
</details>


## 1.YOGL architecture diagram
The structural diagram of the YOGL target detection model will be published after the acceptance of the paper.

## 2.LCSA attention mechanism
The structural diagram and rationale of the LCSA attention mechanism will be published after the acceptance of the paper.

## 3.Dataset
The full data set will be published later.


**3.1 Example image of ID-2024**
![](Insulator_Dataset_Example_Images.png)


## 4.Experiment


**4.1 Comparative Experiments with Mainstream Attention Mechanisms**


![](Different_Attention_Mechanisms.png)


**4.2 Comparison Experiment with Mainstream Lightweight Object Detection Algorithms**


![](Lightweight_Detection_Models2.png)

**4.3 Edge Platform Deployment**


![](Jetson_TX2_NX_EX.png)

## 5 Insulator defect detection results


![](IDD-YOLO_detection_results.png)

## Author's Contact
Email：ly13063414159@163.com



