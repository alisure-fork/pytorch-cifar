
## Accuracy
batch size = 128

| Model             | Acc.        |
| ----------------- | ----------- |
| [LeNet]                                               | 74.64%      |
| [VGG16](https://arxiv.org/abs/1409.1556)              | 93.01%      |
| [ResNet18](https://arxiv.org/abs/1512.03385)          | 93.35%      |
| [ResNet50](https://arxiv.org/abs/1512.03385)          | 93.62%      |
| [ResNet101](https://arxiv.org/abs/1512.03385)         | 93.75%      |
| [MobileNetV2](https://arxiv.org/abs/1801.04381)       | 94.20%      |
| [ResNeXt29(32x4d)](https://arxiv.org/abs/1611.05431)  | 94.73%      |
| [ResNeXt29(2x64d)](https://arxiv.org/abs/1611.05431)  | 94.82%      |
| [DenseNet121](https://arxiv.org/abs/1608.06993)       | 95.04%      |
| [PreActResNet18](https://arxiv.org/abs/1603.05027)    | 95.11%      |
| [DPN92](https://arxiv.org/abs/1707.01629)             | 94.92%      |

## Learning rate adjustment
I manually change the `lr` during training:
    - `0.1` for epoch `[0,150)`
    - `0.01` for epoch `[150,250)`
    - `0.001` for epoch `[250,350)`
