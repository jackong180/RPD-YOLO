# RPD-YOLO: A Cross-modal Interactive Fusion Network for Nighttime Railway Intrusion Pedestrian Target Detection 
This is an official PyTorch implementation for our RPD-YOLO. 

### 1. Dependences
 Create a conda virtual environment and activate it.
 1) conda create --name MOD python=3.9
 2) conda activate MOD
 3) pip install -r requirements.txt

### 2. Datasets download
Download these datasets and create a dataset folder to hold them.

1) M3FD dataset: [M3FD](https://drive.google.com/file/d/1FSfAQQ80UvwE7mXKDAxZZnabUrsM9HHD/view?usp=drive_link)



### 3. Training our RPD-YOLO!
Dataset path, GPU, batch size, etc., need to be modified according to different situations.
```
python train.py
```

### 4. Test our RPD-YOLO

```
python test.py
```


