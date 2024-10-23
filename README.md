# DeepfakeDefenders
外滩大会Deepfake攻防挑战赛参赛记录与其他思路

目前大体的方法：

使用 EfficientNet_b5 预训练模型，epochs = 5

还可以改进的地方：

1. 尝试其他预训练模型
2. 数据集分布不均匀，应该进一步处理
3. 可以采用TTA（Test-Time Augmentation）
