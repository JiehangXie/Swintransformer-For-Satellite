# 飞桨常规赛：遥感影像地块分割- 7月第3名方案

## 项目描述
本项目是利用PaddleSeg分割卫星影像的案例  
在7月的这次比赛中第一次尝试使用了SwinTransformer进行模型训练  
与其他CNN的网络相比，SwinTransformer在这次任务中收敛速度较快  
但效果目前还稍逊于CNN模型，可能是数据增强出现了反向效果，还有就是数据集类别不平均的问题  
后面可以尝试一下修改Loss，缓解一下这些问题


## 项目结构
```
-swin.yml   #本次比赛使用的SwinTransformer的配置文件
-aistudio.ipynb   #AIStudio的Notebook文件
```
## 使用方式
在AI Studio上[运行本项目](https://aistudio.baidu.com/aistudio/projectdetail/1789075)  
Output/best_model目录下包含了本项目58.83057%精度的模型

