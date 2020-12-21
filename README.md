# ADDGCN

[paper](https://arxiv.org/abs/2012.02994). 

## Installation
#### Pytorch 1.0/1.1/1.2.

### Inference for COCO2014

    python main.py --data COCO2014 --data_root_dir ./data --resume ./checkpoint/checkpoint.pth -e -i 576

[get my model](https://pan.baidu.com/s/17Y1knACAo5U6XbV75GUI8w) with password ``4ebj``.

Model | Test size | mAP 
--- |:---:|:---:
ResNet-101 | 448×448 | 79.7
DecoupleNet | 448×448 | 82.2
ML-GCN | 448×448 | 83.0 
ADD-GCN | 448×448 | 84.2
ResNet-101 | 576×576 | 80.0
SSGRL | 576×576 | 84.2
ML-GCN | 576×576 | 84.3
ADD-GCN | 576×576 | 85.2

