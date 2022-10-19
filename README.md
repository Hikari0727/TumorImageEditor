# TumorImageEditor

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

## Table of Contents

- [Background](#background)
- [Install](#install)
- [BraTS](#brats)
- [API](#api)
- [Contributing](#contributing)
- [License](#license)


## Background
Brain tumor segmentation is an important part of medical image processing. Its purpose is to help doctors make accurate diagnosis and treatment. It has important practical value in the field of clinical brain medicine. The research of MRI brain tumor image segmentation has made some significant progress, especially the development of deep learning provides new ideas for the research in this field. We want to create a brain tumor image editor based on natural language processing and deep learning to facilitate doctors to perform relevant image operations.
## Install

use git program with blow code

``` sh
git clone https://github.com/Hikari0727/TumorImageEditor.git
```


## BraTS  

### Data Preparation
MPMRI data set, including training set (1251 cases) and verification set (219 cases)
There are four types of modal data: flair, t1ce, t1, t2. The data size of each mode is 240 x 240 x 155, and they share split labels.
![15341664432255_ pic](https://user-images.githubusercontent.com/104084176/192958891-66f2c1b8-6617-4af8-a1d4-8ef62039b11b.jpg)

Download the BraTS dataset. The structure of the dataset should be as follows:
BraTS2021_00000   
├── BraTS2021_00000_flair.nii.gz  
├── BraTS2021_00000_seg.nii.gz   
├── BraTS2021_00000_t1ce.nii.gz  
├── BraTS2021_00000_t1.nii.gz  
└── BraTS2021_00000_t2.nii.gz  

View images and labels with 3D Slicer
![15351664432860_ pic](https://user-images.githubusercontent.com/104084176/192959008-2c52b316-86c6-4c03-8279-f78049214352.jpg)

### Data Preprocessing 

```
```
We want to encapsulate it into an exe file for direct use by doctors


## API
### We use Xunfei's interface to implement speech recognition（python）

https://user-images.githubusercontent.com/104084176/196747209-1ddeb8a4-a9f5-454f-be1e-1fecc3ca11c3.mp4





## Contributing

JIA CHANGQING<br>
QIU HOUMING <br>
ZHANG XINYI<br>
HUANG QIANYI

### Any optional sections

## License

[NSU © PANDA DRINKING VODKA.](../LICENSE)
