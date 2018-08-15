# MNasNet
[Keras (Tensorflow) Implementation](https://github.com/Shathe/MNasNet-Keras-Tensorflow/blob/master/MNasNet.py) of MNasNet and an example for training and evaluating it on the MNIST dataset. Check also the [eager execution implementation](https://github.com/Shathe/MNasNet-Keras-Tensorflow/blob/master/train_eager.py)

Accordint to the paper: [MnasNet: Platform-Aware Neural Architecture Search for Mobile](https://arxiv.org/pdf/1807.11626.pdf)

## Requirement
* Python 2.7+
* Tensorflow-gpu 1.10

## Train it
Train the [MNasNet model](https://github.com/Shathe/MNasNet-Keras-Tensorflow/blob/master/MNasNet.py) on the MNIST dataset! just execute:
```
python train.py
```

For compiling the model MNAsNet with 4.2M params, execute :
```
python Mnasnet.py
```

## Train in eager execution
Train the [MNasNet model](https://github.com/Shathe/MNasNet-Keras-Tensorflow/blob/master/MNasNet.py) on the MNIST dataset! just execute:
```
python train_eager.py
```



![alt text](https://github.com/Shathe/MNasNet-Keras-Tensorflow/raw/master/mnasnet.png)
