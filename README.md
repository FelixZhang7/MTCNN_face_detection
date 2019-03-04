# MTCNN face detection and alignment tools

## Introduction

  This is a mxnet implementation of [Zhang](https://kpzhang93.github.io/)'s work: Joint Face Detection and Alignment using Multi-task Cascaded Convolutional Neural Networks. 


## Environment

This repository has been tested under the following environment:

-   Python 2.7 
-   Ubuntu 16.04
-   Mxnet-cu80 (==0.11.0)

## Testing

-   Use `python main.py` to test this detection and alignment method.

-   You can change `ctx` to `mx.gpu(0)` to use GPU for faster detection.


see `mtcnn_detector.py` for the details about the parameters. this function use [dlib](http://dlib.net/)'s align strategy, which works well on profile images :) 

## Results

![Detetion Results](https://raw.githubusercontent.com/deepinx/mtcnn-face-detection/master/sample-images/detection_result.png)


