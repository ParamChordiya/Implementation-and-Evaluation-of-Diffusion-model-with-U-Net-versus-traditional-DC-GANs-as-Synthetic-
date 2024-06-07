# ECE 285 Project: Implementation and Evaluation of Diffusion model with U-Net versus traditional DC-GANs as Synthetic Image Generators

This repository contains the project work done for ECE 285 - Introduction to Visual Learning at UCSD ECE Department. The project focuses on understanding how different synthetic image generation methods such as the Diffusion model and GANs work at their roots and how efficient they are by implementing them from scratch. We also try to improve these models rigorously by hyper parameter tuning as well as implementing a U-NET architecture for denoising in the Diffusion model.

## Abstract

Generative Adversarial Networks (GANs) have revolutionized synthetic image generation. This project evaluates the performance of two generative models, Diffusion Models with U-Net architecture and Deep Convolutional GANs (DCGANs), for COVID-19 lung image synthesis. The models are implemented and optimized through hyperparameter tuning. The Diffusion Model denoises samples from Gaussian noise to produce realistic images, while the DCGAN uses adversarial learning to generate synthetic images. Performance is tracked by measuring training times and plotting losses per epoch.
Image quality is assessed using the Frechet Inception Distance (FID) score, and visual comparisons are made. This comparative analysis provides insights into the strengths and weaknesses of each approach.

## Project Report

The Project report can be found at - [Project Report](https://github.com/ParamChordiya/ECE-285-Project-UCSD/blob/main/Final_Project_Report___ECE_285.pdf)
## Contributors

- Param Chordiya
- Riya Joshi
