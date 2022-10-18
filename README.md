# Boundary-Guided Transformer

## Requirements

- [Anaconda](https://www.anaconda.com/download/)
- [PyTorch](https://pytorch.org)

```
conda install pytorch torchvision cudatoolkit=11.0 -c pytorch
```

- timm

```
pip install timm
```

- opencv

```
pip install opencv-python
```

##data
#



## Usage

### Train model

```
python train.py 
optional arguments:
--data_path                   Data path for dataset £¨default='/home/shenjj/BGTR/data/'£©
--crop_h                      Crop height for training images 
--crop_w                      Crop width for training images 
--batch_size                  Number of data for each batch to train 
--epochs                      Number of sweeps over the dataset to train 
--save_path                   Save path for results 
```

### Eval model

```
python viewer.py --model_weight model.pth
optional arguments:
--data_path                   Data path for dataset 
--model_weight                Pretrained model weight 
### An example of a test:
(1.png)
The model are trained using PyTorch 1.10.1 with a NVIDIA GeForce RTX 3090 GPU. The size of the input image is set to 512 X 512 and batch size set to 4.
trained models for Boundary-Guided Transformer can be found in xx
# Boundary-Guided Transformer
