#  Shenzhen built-up area （SZBUA）sample dataset

## Overview

This dataset was created from Gaofen-2 satellite imagery covering Shenzhen, China. It includes scene level sample sets of built-up and non built-up areas, as well as pixel level annotated test sets.

## Training Dataset Information

- **Image Channels:** Three channels of RGB with panchromatic sharpening
- **Spatial Resolution:** 1 m
- **Total number of images**: 9808 
- **Image size**: 112 × 112


### Data Distribution Statistics

|                    | Built-up Areas | Non-built-up Areas |
|---------------------|----------------|--------------------|
| Manually Selected Sample Count | 1226 | 1226 |
| Sample count obtained through data augmentation | 3678 | 3678|
| Total Sample Count | 4904 | 4904 |


**Note:** During the data augmentation process, image flipping was adopted, with 1226 selected built-up and non built-up samples flipped at 90, 180, and 270 degrees, resulting in a fourfold increase in sample data.

## Test Dataset Information

The test set includes satellite images of five sub-regions in Shenzhen, with the following sizes:

- Test 1: 8960 × 7840
- Test 2: 10,080 × 8960
- Test 3: 8400 × 8400
- Test 4: 8960 × 8960
- Test 5: 8400 × 8400

## Usage

This dataset may provide necessary data reference and support for researchers in the detection, segmentation, and mapping of urban built-up areas. Previous studies related to this dataset can refer to:  
[1]Chen, Y.; Peng, F.; Yao, S.; Xie, Y. Lightweight Multilevel  Feature- Fusion  Network for Built-Up Area Mapping from Gaofen-2 Satellite Images. Remote Sens. 2024, 16.  
[2]Chen, Y.; Yao, S.; Hu, Z.; Huang, B.; Miao, L.; Zhang, J. Built-up Area Extraction Combing Densely Connected Du-al-Attention Network and Multi-Scale Context. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 2023.  
If you have any questions or suggestions, please contact us：chenyixiang@njupt.edu.cn; 1022173204@njupt.edu.cn

