# Pytorch Tutorial

This tutorial is a simple example of using Pytorch to train a simple neural network. 
Let's take a linear regression as an example ( *y = 2x + 3* ).
We will use a simple dataset to train a linear regression model.
You will learn about Dataset, DataLoader, Model, Loss, Optimizers, Training, Evaluation, and how to save and load models. 🎉

## Install Dependency
```shell
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```

## Begin Training

```shell
cd torch_tutorial
python main.py --device 0 --cpu --seed 0 --weight_decay 0.001 --lr 0.01 --epochs 3000
```

## Begin Inferencing

```shell
cd torch_tutorial
python inference.py
```