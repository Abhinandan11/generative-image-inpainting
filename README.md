# generative-image-inpainting


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

### 2. Downloading the dataset
To download the CelebA dataset, go to Kaggle:
```
https://www.kaggle.com/jessicali9530/celeba-dataset
```
We need images and list_attr_celeba.txt
### 3. Training
```bash
$ python main.py
```
[Refer config.py for available arguments]
### 4. Testing
```bash
$ python main.py --mode test
```
