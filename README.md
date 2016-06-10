## Simple Alexnet using Tensorflow through TFLearn

### Install TFLearn

```
pip install git+https://github.com/tflearn/tflearn.git
```

### Extract sample data

```
tar xvzf 17flowers.tar.gz
```

### Training

```
python tflearn_alexnet_end2end.py
```

### Tensorboard

```
tensorboard --logdir output
```