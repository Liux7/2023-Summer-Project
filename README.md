# CNN_PyTorch

1. 首先实现基于MNIST数据集的手写识别 (v0)

python=3.6 cuda=10.2 

CPU train speed: 100%|██████████| 468/468 [07:46<00:00,  1.00it/s]

CPU test speed : 100%|██████████| 78 / 78 [00:18<00:00,  4.12it/s]

GPU train speed: 100%|██████████| 468/468 [01:01<00:00,  7.56it/s]

GPU test  speed: 100%|██████████| 78 / 78 [00:02<00:00, 26.43it/s]

注意在使用GPU时，要把GPU 1的copy功能关闭

train speedup: 7.56x

test  speedup: 6.41x

2. 尝试输入其他图片

