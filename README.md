# ERFNet

This code is a toolbox that uses Torch library for training and evaluating the ERFNet architecture. 

## Publications

If you use this software in your research, please cite our publications:

**"Efficient ConvNet for Real-time Semantic Segmentation"**, E. Romera, J. M. Alvarez, L. M. Bergasa and R. Arroyo, IEEE Intelligent Vehicles Symposium (IV), June 2017.

**"ERFNet: Efficient Residual Factorized ConvNet for Real-time Semantic Segmentation"**, E. Romera, J. M. Alvarez, L. M. Bergasa and R. Arroyo, paper extension for T-ITS journal **[currently under review]**.


## Packages

* [train](train) contains tools for training the network for semantic segmentation.
* [eval](eval) contains tools for evaluating/visualizing the network's output.
* [trained_models](trained_models) Contains the trained models used in the papers.

## Requirements
The Cityscapes dataset, which can be downloaded [here](https://www.cityscapes-dataset.com/).

Torch Library [(installation tutorial)](http://torch.ch/docs/getting-started.html) with CUDA and CuDNN backends.

NOTE: The code has been tested in Ubuntu 16.04 and Torch7 with CUDA 8.0 and CuDNN 5.1. It should work with other versions but we cannot guarantee it.

## Usage

Usage and examples for either [training](train) or [evaluating](eval) the models are described in the READMEs of each section.


## License

This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License, which allows for personal and research use only. For a commercial license please contact the authors. You can view a license summary here: http://creativecommons.org/licenses/by-nc/4.0/
