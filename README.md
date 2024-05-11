# Super Resolution Models

That's my course project on improving image quality with machine learning.

All code is in `main.ipynb`. All model weights except `SRGAN` are in this repository.

## Overview

In this work, algorithms for improving image quality using neural networks were considered:

- `SRCNN` as a basic solution to the presented problem showed satisfactory results;
- `FSRCNN` as an improvement to the previous method presented the best performance;
- `SRGAN` as a potentially strong model, which, unfortunately, showed worst result.

The results of models based on convolutional layers can be called positive, since they showed superior quality over interpolation algorithms.

It was also shown that splitting into single-channel images gives an increase in the metric and only slightly affects the computational costs.

You can see the results in the pictures:

![image](https://github.com/Dragon066/Super-Resolution-Models/assets/74358737/dd841d28-6ed3-4928-965a-b1f4e75d6e73)

![image](https://github.com/Dragon066/Super-Resolution-Models/assets/74358737/deafe459-3677-46c3-9f36-5a48aebad358)

## Dataset

This dataset from Kaggle was used during training: https://www.kaggle.com/datasets/adityachandrasekhar/image-super-resolution/data

## References

- [Kaggle Image Super Resolution Dataset](https://www.kaggle.com/datasets/adityachandrasekhar/image-super-resolution/data)
- [Deep Learning for Image Super Resolution](https://arxiv.org/pdf/1902.06068)
- [Image Super Resolutiion: A Comprehensive Review](https://blog.paperspace.com/image-super-resolution/)
- [SRCNN PyTorch implementation](https://github.com/Fivefold/SRCNN)
- [FSRCNN PyTorch implementation](https://github.com/Nhat-Thanh/FSRCNN-Pytorch)
- [SRGAN PyTorch implementetion](https://www.kaggle.com/code/minawagihsmikhael/srgan-image-super-resolution-pytorch/notebook)
