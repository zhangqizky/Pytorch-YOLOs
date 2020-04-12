## 文件结构

- train.py 训练代码
- test.py 测试脚本
- vgg_yolo.py 和resnet_yolo.py是分别vgg一系列模型和resnet一系列模型做backbone的定义
- dataset.py 数据的加载，包括数据增强，bbox处理，label生成
- visualize.py 如果可以使用visdom，可以对训练过程做一个可视化
- yoloLoss.py yolo超复杂的损失函数定义
