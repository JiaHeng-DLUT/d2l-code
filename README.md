# d2l-code

## Conv

|    Net     |                             New                              |  Acc  |
| :--------: | :----------------------------------------------------------: | :---: |
|   LeNet    |                   conv + sigmoid + linear                    | 0.903 |
|  AlexNet   | 1. conv + relu + maxpool<br/>2. sigmoid -> relu<br/>3. dropout<br/>4. data augmentation | 0.928 |
|   VGGNet   |                          vgg block                           | 0.927 |
|    NiN     |                1. 全卷积<br/>2. 全局平均池化                 | 0.906 |
| GoogLeNet  |                           并行网络                           | 0.920 |
| LeNet + BN |                              BN                              | 0.905 |
|   ResNet   |                              +                               | 0.939 |
|  DenseNet  |                             cat                              | 0.939 |

