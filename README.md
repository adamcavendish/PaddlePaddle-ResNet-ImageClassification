 # 百度深度学习框架 PaddlePaddle 使用 ResNet 做图像分类任务
 
视频地址：

[B站](https://www.bilibili.com/video/av35821372/)

代码主体：

[Jupyter Notebook](Image-Classification.ipynb)
 
---

Jupyter Notebook
* http://jupyter.org/

PaddlePaddle
* [PaddlePaddle 图像分类模型库](https://github.com/PaddlePaddle/models/tree/develop/fluid/PaddleCV/image_classification)
* [PaddlePaddle 官方文档](http://www.paddlepaddle.org/documentation/docs/zh/1.1/beginners_guide/index.html)

常用库
* [Numpy 矩阵库](http://www.numpy.org/)
* [Pillow 图像库](https://pillow.readthedocs.io/)

ResNet 论文
* [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)
* [Identity Mappings in Deep Residual Networks](https://arxiv.org/abs/1603.05027)

批正则化 (Batch-Normalization) 论文
* [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/abs/1502.03167)

ImageNet 数据集论文和下载链接
* [ImageNet: A large-scale hierarchical image database](http://www.image-net.org/papers/imagenet_cvpr09.pdf)
* 数据集下载 (需要官网注册，需要160G左右硬盘空间):
  * [官网](http://www.image-net.org/)
  * [PaddlePaddle 脚本下载](https://github.com/PaddlePaddle/models/tree/develop/fluid/PaddleCV/image_classification#data-preparation)
  
Natural Images 数据集论文和下载链接
* [Effects of Degradations on Deep Neural Network Architectures](https://arxiv.org/abs/1807.10108)
* [Kaggle 下载链接](https://www.kaggle.com/prasunroy/natural-images)

ResNet-50 模型预训练参数下载：

(下载 PaddlePaddle ResNet-50 预训练模型参数，并解压于当前文件夹相同目录)

* [直接下载链接](http://paddle-imagenet-models.bj.bcebos.com/resnet_50_model.tar)
* [模型库链接](https://github.com/PaddlePaddle/models/tree/develop/fluid/PaddleCV/image_classification#supported-models-and-performances)
