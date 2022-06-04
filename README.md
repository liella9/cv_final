# cv_final

### Faster R-CNN

#### 训练步骤
1. 提前准备好数据集
2. 提前下载好对应预训练模型权重(要重命名)backbone: https://download.pytorch.org/models/fasterrcnn_resnet50_fpn_coco-258fb6c6.pth
5. 使用```train_resnet50_fpn.py```训练脚本
6. 最终得到的模型以及loss和mAP曲线保存

#### 测试步骤
1. 使用predict.py
2. train_weights设置为训练好的模型,original_img为待测试的图片
3. 得到带得分和类别的box
