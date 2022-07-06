# [SA-UNet: Spatial Attention U-Net for Retinal Vessel Segmentation(ICPR 2020)](https://arxiv.org/abs/2004.03696)





### Datasets
#### Data augmentation:
1. [keras_dataAug.py](keras_dataAug.py) <br>
(1) Random rotation; <br>
(2) adding Gaussian noise; <br>
(3) color jittering; <br>
2.[flip.py](flip.py)<br>
(4) horizontal, vertical and diagonal flips.

if you do not want to do above augmentation,just download it from two [data].zip above

## Quick start 

### Training
Run [Train_drive.py](Train_drive.py)  or [Train_chase.py](Train_chase.py)
### Testing
Run [Eval_drive.py](Eval_drive.py) or [Eval_chase.py](Eval_chase.py)



## Environments
Keras 2.3.1  <br>
Tensorflow==1.14.0 <br>

## About Keras

Keras is a minimalist, highly modular neural networks library, written in Python and capable of running on top of either TensorFlow or Theano. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result with the least possible delay is key to doing good research.

Use Keras if you need a deep learning library that:

allows for easy and fast prototyping (through total modularity, minimalism, and extensibility).
supports both convolutional networks and recurrent networks, as well as combinations of the two.
supports arbitrary connectivity schemes (including multi-input and multi-output training).
runs seamlessly on CPU and GPU.
Read the documentation [Keras.io](http://keras.io/)

Keras is compatible with: Python 2.7-3.5.



# If you are inspired by our work, please cite these papers.


#### Structured dropout convolutional block
@INPROCEEDINGS{8942005,  <br>
author={C. {Guo} and M. {Szemenyei} and Y. {Pei} and Y. {Yi} and W. {Zhou}}, <br> 
booktitle={2019 IEEE 19th International Conference on Bioinformatics and Bioengineering (BIBE)},   <br>
title={SD-Unet: A Structured Dropout U-Net for Retinal Vessel Segmentation},   <br>
year={2019},  <br>
volume={},  <br>
number={},  <br>
pages={439-444},}<br>


@article{Guo2020SAUNetSA,<br>
  title={SA-UNet: Spatial Attention U-Net for Retinal Vessel Segmentation},<br>
  author={Changlu Guo and Marton Szemenyei and Yugen Yi and Wenle Wang and Buer Chen and Changqi Fan},<br>
  journal={ArXiv},<br>
  year={2020},<br>
  volume={abs/2004.03696}<br>
}<br>
