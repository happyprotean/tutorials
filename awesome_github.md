# Awesome github repository  

## knowledge distillation

- [awesome-knowledge-distillation](https://github.com/dkozlov/awesome-knowledge-distillation)  有关知识蒸馏的repo集合，包括论文、代码
- [knowledge_distillation_zoo](https://github.com/AberHu/Knowledge-Distillation-Zoo) :各种知识蒸馏方法的简单实现
- 学习拟合target
  - [KD](https://www.bilibili.com/video/av87124082?from=search&seid=14269047959253479288):Hinton论文的pytorch实现，B站视频
  - NAS+KD：Search to Distill
  - [Deep mutual learning](https://github.com/chxy95/Deep-Mutual-Learning) : pytorch实现多个学生网络相互之间进行学习，但是其目的不是为了压缩模型，而是提升模型的性能   [还有tf实现](https://github.com/YingZhangDUT/Deep-Mutual-Learning) 
- 学习拟合特征
  - [FitNets](https://github.com/adri-romsor/FitNets)：学生网络去学习教师网络的feature map，代码基于theano [另一个实现](https://github.com/Jashmi/FitNets) : **too old, looked**
  - [attention transfer](https://github.com/szagoruyko/attention-transfer): 学生网络学习教师网络的热力图， **looked**， csdn有代码的[注释](https://blog.csdn.net/weixin_43316934/article/details/89457127)
  - [Distillation of the boundaries](https://github.com/bhheo/AB_distillation) : AAAI2019论文，值得一看
- 学习相互关系
  - [Relational knowledge distillation](https://github.com/lenscloth/RKD): 学习examples的输出之间的关系
- [Teacher-Assistant-Knowledge-Distillation](https://github.com/imirzadeh/Teacher-Assistant-Knowledge-Distillation): 在教师网络和学生网络之间增加assistant，帮助其进行学习 -- to look
- [self distillation](https://github.com/cardwing/Codes-for-Lane-Detection) 自己训练自己，不需要教师网络





## 数据结构刷题

[coding-interviews](https://github.com/shenweichen/coding_interviews)  python实现剑指offer



## Keras

[deep learning with keras](https://github.com/erhwenkuo/deep-learning-with-keras-notebooks) Keras的教程材料，有yolo等

[python深度学习](https://github.com/fchollet/deep-learning-with-python-notebooks)：keras之父写的keras教程，值得一看



## Pytorch

[pytorch handbook](https://github.com/zergtant/pytorch-handbook)： 一本开源书籍，介绍pytorch的基本操作

[pytorch for research learning](https://github.com/yunjey/pytorch-tutorial): pytorch教程，github标星很高



## 人脸属性识别

[FaceAttr-Analysis](https://github.com/Hawaii0821/FaceAttr-Analysis) : pytorch，很多不同的网络实现，如SENet，Resnet等

[face-attribute-prediction](https://github.com/d-li14/face-attribute-prediction) ： pytorch，使用ResNet和MobileNet

[FaceAttribute](https://github.com/WynMew/FaceAttribute) : pytorch，使用focal loss对六个属性进行预测