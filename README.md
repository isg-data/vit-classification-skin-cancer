# Skin Cancer Detection utilizing Deep Learning: Classification of Skin Lesion Images using a Vision Transformer (ViT)

## Overview
In this project we implement a deep learning pipeline for classifying skin lesions using Vision Transformers (ViT). Leveraging the HAM10000 dataset, we compare the performance of pretrained ViT L16 and ViT L32 models against baseline models such as Decision Tree and k-Nearest Neighbor as well as pretrained CNNs and smaller ViT configurations. The goal is to support early, automated detection of melanoma, the deadliest form of skin cancer.

## Results
The results in our experiment show that ViT L16 achieves the highest accuracy at 92.79%, with a melanoma recall of 56.10%. ViT L32 follows with 91.57% accuracy and 58.54% recall. Both models outperform traditional classifiers and smaller ViTs, showing strong potential for accurate and automated skin cancer detection.

## Citation
If you find our work helpful, please consider citing it:

Working paper: https://arxiv.org/abs/2407.18554

```bibtex
@article{flosdorf2024skin,
  title={Skin Cancer Detection utilizing Deep Learning: Classification of Skin Lesion Images using a Vision Transformer},
  author={Flosdorf, Carolin and Engelker, Justin and Keller, Igor and Mohr, Nicolas},
  journal={arXiv preprint arXiv:2407.18554},
  year={2024}
}
````
