# Fast.ai

## Introduction <br/>

For those who doesn't know **[Fast.ai](https://www.fast.ai/)**, It's an AI library built on top of **PyTorch** and it really changed the game. With a few lines of code you can build a running Machine Learning model that can produce a high accuracy.

## Prerequestes <br/>
You first need to install `pytorch` framework using `pip install torch` and then you need to install Fast.ai library using `pip install fastai` and you are ready to go.

## Imports <br/>

You only need to import these two classes <br/>
`from fastai.vision import *`<br/>
`from fastai.metrics import *`


## Notebooks

### 1. Binary Classification <br/>

Fast.ai took binary classification problems into a whole new level with **Transfer Learning** using a pretrained model we can build a binary classifier with a few amount of data and produce a very decent results. In this notebook, I tried to implement a very basic binary classification problem **"Cat or dog"** and using a small dataset from **Kaggle** and **ResNet34** model and only 10 epoches, I was able to get build a model with very good numbers.<br/>




### 2. Multi-class Classification <br/>

Another kind of Classifiers in which we try to build a model that can distinguish diffrent kinds of **Bears** baised on a dataset we have collected from **Google Images**. Using The same model from the previous notebook (**ResNet34**) and again a very decent numbers with only couple of minutes of training. <br/>

![](https://user-images.githubusercontent.com/47199425/86521343-c41ab580-be4f-11ea-9743-408065305898.PNG) <br/>

P.S: This notebook is just the "Hello World" of the library <br/>


