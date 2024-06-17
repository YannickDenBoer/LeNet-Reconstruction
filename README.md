# LeNet Reconstruction
This repository contains a reconstruction of the popular LeNet-5 archetecture and four model variants to improve the model on the FashionMNIST dataset. 
This code was submitted for the Computer Vision course at Utrecht University
The code and report are co-authored by Eva Kato

![image](https://github.com/YannickDenBoer/LeNet-Reconstruction/assets/95358977/80e21629-dfef-426a-aa97-955dfaf8e660)

## Variants
1. LeNet + More Kernels
2. Variant1 + Dropout layers
3. Variant2 + L2 Regularization
4. Variant3 + Decreased Learning Rate

| Model Name | Training top-1 accuracy (%) | Validation top-1 accuracy (%) | Epoch |
|------------|-----------------------------|-------------------------------|-------|
| LeNet-5    | 95.5%                       | 90.7%                         | 14    |
| Variant 1  | 95.9%                       | 91.7%                         | 10    |
| Variant 2  | 94.8%                       | 91.5%                         | 13    |
| Variant 3  | 94.8%                       | 91.6%                         | 14    |
| Variant 4  | 94.5%                       | 92.0%                         | 14    |

## Further
The first part contains code to enable Cuda. But in this version tensors are not moved to the gpu.
