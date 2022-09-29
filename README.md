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

### Since AI programs are not user-friendly.We decided to integrate AI into visualization programs to assist doctors in diagnosis.
The project is divided into two main parts, the first of which is NLP. The doctor uses voice input instructions. The second part is image editing, including functions such as the designation of the image zoom in and out area. Physician assistance is also given to the area of the delineated tumor.
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

### Waiting for updating


## Contributing

JIA CHANGQING<br>
QIU HOUMING <br>
ZHANG XINYI<br>
HUANG QIANYI

### Any optional sections

## License

[NSU © PANDA DRINKING VODKA.](../LICENSE)
