# EViFT - Event-Visible frame Fusion Transformer

## Platform

Python >= 3.8  
Pytorch >=1.0

## Training Dataset

[MS-COCO 2014](http://images.cocodataset.org/zips/train2014.zip) (T.-Y. Lin, M. Maire, S. Belongie, J. Hays, P. Perona, D. Ramanan, P. Dollar, and C. L. Zitnick. Microsoft coco: Common objects in context. In ECCV, 2014. 3-5.) is utilized to train our auto-encoder network.

[KAIST](https://sites.google.com/view/multispectral/home) (S. Hwang, J. Park, N. Kim, Y. Choi, I. So Kweon, Multispectral pedestrian detection: Benchmark dataset and baseline, in: Proceedings of the IEEE conference on computer vision and pattern recognition, 2015, pp. 1037–1045.) is utilized to train the RFN modules.

## Acknowledgement

This codebase is built on top of [Image-Fusion-Transformer](https://github.com/Vibashan/Image-Fusion-Transformer) by [Vibashan](https://github.com/Vibashan).
