# Gaze-Project
Gaze project for ML course in SJTU. 

### Overview
The Gaze project consists of a white-box attack task and a black-box attack task. The target model include CNN and ViT neural networks. The test data includes 1000 sampled images from ImageNet validate datasets. 

### Models
We suggest to use models provide by [timm](https://github.com/rwightman/pytorch-image-models). Timm provide many awesome Pytorch pretrain models. 
Model 1: Vision transformer
```
import timm
model = timm.create_model('vit_base_patch16_224', pretrained=True)
model.eval()
```

#### Model 


### Reference 
1. 
