# Attack-Project
Adversarial Attack project for ML course in SJTU. 

### Overview
The Gaze project consists of a white-box attack task and a black-box attack task. The target model include CNN and ViT neural networks. The test data includes 1000 sampled images from ImageNet validate datasets.   

### Models 
We suggest to use models provide by [timm](https://github.com/rwightman/pytorch-image-models). Timm provide many awesome Pytorch pretrain models.   
Model 1: ResNet50
```
import torchvision.models as models
resnet50 = models.resnet18(pretrained=True)
```
Model 2: Vision transformer
```
import timm
model = timm.create_model('vit_base_patch16_224', pretrained=True)
model.eval()
```

#### Datasets 
Find datasets in [Baidu Wangpan](https://pan.baidu.com/s/1nt5guRByhu-hVo-98fj0SA) (Password：wawy) and  [Google Drive](https://drive.google.com/file/d/1wMpxCPfloy13UlYxhFxM_5fn7Rr2kEPm/view?usp=sharing).

### Reference 
1. Intriguing Properties of Vision Transformers [pdf](https://proceedings.neurips.cc/paper/2021/file/c404a5adbf90e09631678b13b05d9d7a-Paper.pdf)

