# AER-SwinT
The source code for Attention Enhanced Residual Swin-Transformer

<div align=center><img width="1200" height="380" src="https://github.com/ShengtianSang/AER-SwinT/blob/main/figures/Framework%20main.png"/></div>
<p align="left"> 
The overview of our method. 
</p>



## Requirements
* albumentations==1.0.0
* inplace_abn==1.1.0
* matplotlib==3.4.2
* numpy==1.22.2
* opencv_python_headless==4.5.2.54
* pretrainedmodels==0.7.4
* segmentation_models_pytorch==0.2.0
* torch==1.8.0
* torchvision==0.9.0

## Data
In order to make it easier for the readers to reproduce and understand the code, I have provided a small amount of example data used in our experiment under the **dataset** folder, where provides six training, validation and test images.

## File declaration


**main.py**: The codes for training, validating and testing.

## Run the codes
Install the environment.
```bash
pip install -r requirements.txt
```

Train and test the model.
```bash
python main.py
```
