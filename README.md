# RPSW
Official PyTorch implementation for paper:  [Sliced Wasserstein with Random-Path Projecting Directions](https://arxiv.org/abs/2401.15889)


Details of the model architecture and experimental results can be found in our papers.

```
@article{nguyen2024sliced,
  title={Sliced Wasserstein with Random-Path Projecting Directions},
  author={Khai Nguyen and Nicola Bariletto and Nhat Ho},
  booktitle={nternational Conference on Machine Learning},
  year={2024},
  pdf={https://arxiv.org/pdf/2401.15889.pdf}
}
```
Please CITE our paper whenever this repository is used to help produce published results or incorporated into other software.

This implementation is made by [Khai Nguyen](https://khainb.github.io).

## Requirements
First, please install "power_spherical" package at https://github.com/nicola-decao/power_spherical, then run
```
pip install -r requirements.txt
```

## What is included?
* Gradient flow
* Diffusion-GAN


## Gradient flow 
```
cd GradientFlow
python main.py
```

## Diffusion-GAN
Please read the README file in the [denoising-diffusion-gan](denoising-diffusion-gan) folder.

## Acknowledgment
Diffusion-GAN code is largely based on [denoising-diffusion-gan](https://github.com/NVlabs/denoising-diffusion-gan). 