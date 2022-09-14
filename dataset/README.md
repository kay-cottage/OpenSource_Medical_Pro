# Medical_CLIP

## 介绍：

 * 以文本编码器及图像编码器作为老师模型，训练3模态及以上的多模态模型
 * 基于openai RN50重构图像编码器和文本编码器代码及其各自的预训练权重
 * 提供多模态中文CLIP网络微调、训练的相关代码（openai-CLIP finetune and train）
 * 包含CLIP多语言模型、ViT-B-32、封神榜模型、以及最大的中文多模态图像文本对数据集Wukong的网盘下载地址
 * 该项目为个人想法的小实现；旨在基于大规模预训练模型，尝试融合（eeg、语音、图像、文本）4模态信号训练模拟人类情感

## Paper

* openai-CLIP([CVPR2021](https://arxiv.org/abs/2103.00020))


## 环境 (Environment)

* CUDA CUDNN(非必须）
* sentence-transformers
* python 3.7
* numpy
* pandas
* Windows
* Pythorch
* Pillow



## 相关仓库
| 模型 | 网盘路径 | 提取码 |
| :----- | :----- | :----- |
clip-ViT-B-32-multilingual-v1 | https://pan.baidu.com/s/1da8J9WUBTTePZ0whQqoTKw   | ws3y
clip-ViT-B-32 | https://pan.baidu.com/s/1HUCODtIpScX19P7m8c1cuQ  | 81sb 
clip-vit-base-patch32 | https://pan.baidu.com/s/14al-fMZ1VOzjTJ1FI9d7AQ  | 83wo
Taiyi-CLIP-Roberta-102M-Chinese | https://pan.baidu.com/s/1Sy6ZUnZ4S5P1C-wiOdi4fQ h | skt8 
RN50_Text_Encoder | https://pan.baidu.com/s/1Mpx3aDMTRePcBg5eFcJ26w | ud3f 
RN50_Images_Encoder | https://pan.baidu.com/s/1n176W2o6U4IXjGLljn5YDA  | vozu 

## Wukong数据集（1亿个图像文本对）：
  
  网盘链接：https://pan.baidu.com/s/1VrhnDy0xqqW4--VgBBUwAg 
  提取码：knzb 

## 使用方法


## 未完待续
