# MonoStereoFusion

<img width="1200" src="https://github.com/YuhuaXu/MonoStereoFusion/blob/main/pipeline.png"/></div>

This repository contains the code and dataset for our paper *Yuhua Xu, Xiaoli Yang, Yushan Yu, Wei Jia, Zhaobi Chu, Yulan Guo. Depth Estimation by Combining Binocular Stereo and Monocular Structured-Light, CVPR 2022*.

## Requirements
The code has been tested with PyTorch 1.8.1 and Cuda 10.1.

## Dataset
We provided the MonoBinoStereo dataset, check /MonoBinoStereo-dataset

The dataset includes:

- passive stereo images
- stereo images with asymmetric textures (the left images are passive, and the right images are with speckles)
- depth maps generated from the structured light subsystem. These depth maps are aligned with the left images.
- the ground truth disparity maps generated by the space-time stereo methods
- parameters of cameras

## Pre-trained model
We provide pre-trained models RAFT-OM-G and RAFT-O, under the folder /trained-models

## Evaluation
We provided a script to get the MonoBinoStereo dataset benchmark result. 

evaluation.py provides an example usage.

## Download
OneDrive Link: https://1drv.ms/u/s!AhORN5PjOtgJgTFmL8LsM94BSLvu?e=faAQjQ

## License agreement
This dataset is made freely available to academic and non-academic entities for non-commercial purposes such as academic research, teaching, scientific publications, or personal experimentation.

## Acknowledgements
Part of the code is adopted from the previous works: RAFT, PSMNet. We thank the original authors for their contributions.



