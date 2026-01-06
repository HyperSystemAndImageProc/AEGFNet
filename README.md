# AEGFNet

This repository provides the code for the methods and experiments presented in our paper '**Adaptive Edge-Guided Fusion Network for Remote Sensing Image Change Detection**'.


![本地路径](network.png )




## Datasets

Download the building change detection dataset. 

- [SYSU]
- [WHU-CD](https://study.rsgis.whu.edu.cn/pages/download/)
- [LEVIR-CD](https://justchenhao.github.io/LEVIR/)

Prepare datasets into following structure,

```
├─train
    ├─A
    ├─B
    ├─label
├─val
    ├─A
    ├─B
    ├─label
├─test
    ├─A
    ├─B
    ├─label
```

In the following experiments, each image in the dataset is pre-cropped into multiple image patches of size 256 × 256.


## Preparation

* Install dependencies using
```
pip install -r requirements.txt
```


## Train

* Change the root address in the train section to your dataset address, for example: root = 'D:\dataset\LEVIR-CD'.

* Run main_train.py to start training. 

* Run eval_cd.py to start testing. 





