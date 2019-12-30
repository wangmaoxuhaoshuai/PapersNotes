# EfficientDet: Scalable and Efficient Object Detection
## 一、摘要
提出了两种优化模型效率的方法
- 提出带权重的双向特征金字塔网络BiFPN，用于更简单快捷地进行特征融合。
- 提出了一种复合缩放方法，该方法可以同时对主干网络、特征提取网络以及预测类别和坐标的网络中的分辨率、深度、宽度进行统一地缩放。

提出了新的目标检测框架EfficientDet。
值得一提的是，EfficientDet-D7在COCO数据集上mAP达到51.0的同时，参数量只有52M并且FLOPS为326B，
相比之前最好的检测模型参数量小了4倍，FLOPS小了9倍，mAP上升了0.3%。