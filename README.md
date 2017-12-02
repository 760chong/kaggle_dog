
# kaggle_dog
kaggle Dog Breed Identification

代码主要参考 @fiercex https://github.com/fierceX/Dog-Breed-Identification-Gluon

不同的地方：

  1)网络多了一个dropout且参数有变化
  
  2)输入的图像大小inception_v3从原299x299 变成 363x363,resnet152_v1从
  224x224 变成 288x288
  
  3)分数inception_v3: 0.23179,resnet152_v1 :0.27800
  
  4)分数组合inception_v3,resnet152_v1:0.21224
  
  5)具体的组合代码请参考：@fiercex https://github.com/fierceX/Dog-Breed-Identification-Gluon
