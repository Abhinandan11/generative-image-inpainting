# generative-image-inpainting

A PyTorch implementation of [Generative Image Inpainting with Contextual Attention](https://arxiv.org/abs/1801.07892)

## Dependencies
* [Python 3.6+](https://www.continuum.io/downloads)
* [PyTorch 1.0.1](http://pytorch.org/)

<br/>

## Usage

### 1. Cloning the repository
```bash
$ git clone https://github.com/Abhinandan11/generative-image-inpainting.git
$ cd generative-image-inpainting/
```

### 2. Installing Requirements
```bash
$ pip install -r requirements.txt
```

### 3. Downloading the dataset
To download the CelebA dataset, go to Kaggle:
```
https://www.kaggle.com/jessicali9530/celeba-dataset
```
We need **images** and **list_attr_celeba.txt**. Put images in ```data/CelebA/images/```, and list_attr_celeba.txt in ```data/```
### 4. Training
```bash
$ python main.py
```
[Refer config.py for additional arguments]
### 5. Testing
```bash
$ python main.py --mode test
```
[Refer config.py for additional arguments]
