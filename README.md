# PanNuke Semantic Segmentation Project

This repository contains implementations of deep learning models for nuclei instance segmentation and classification using the PanNuke dataset. The project explores different architectural approaches including U-Net and DeepLabV3+ with ResNet50 for semantic segmentation tasks in histopathological images.

## Dataset

The PanNuke dataset consists of:
- 189,744 labeled nuclei with instance segmentation masks
- 7,901 images (256×256 pixels)
- 19 tissue types
- 5 cell categories (Neoplastic, Inflammatory, Connective, Dead, Epithelial)
- Images captured at x40 magnification (0.25 µm/pixel resolution)

## Implementation

The project includes three main implementations:
1. Basic U-Net architecture
2. ResNet50 with U-Net
3. ResNet50 with DeepLabV3+

Each implementation is available in separate Jupyter notebooks in the `notebooks/` directory.

## Methods

The implementations utilize state-of-the-art deep learning architectures for semantic segmentation:
- U-Net: Convolutional network architecture specifically designed for biomedical image segmentation
- ResNet50: Deep residual network used as a backbone for feature extraction
- DeepLabV3+: Advanced semantic segmentation architecture incorporating atrous convolutions

## Reference Papers

- [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)

## License

This project is licensed under the terms included in the LICENSE file.

## Author

Nikolaos Tsopanidis (aivc24022)
