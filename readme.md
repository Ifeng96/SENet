# CIFAR100数据集

# 安装依赖库

```
pip install -r requirements.txt
```



# 训练

命令行执行
```
python train.py -net seresnet18 -gpu
```



# 测试

命令行执行

```
python test.py -net seresnet18 -weights path_to_seresnet18_weights_file
```



注意：seresnet18也可以换成seresnet34 / seresnet50 / seresnet101 / seresnet152