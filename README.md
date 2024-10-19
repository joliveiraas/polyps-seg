# Polyps Segmentation: U-Net and EfficientNetB0 Encoder

## Project Overview
This project is a experiment for the semantic segmentation of gastrointestinal polyps in colonoscopy images using [U-Net](https://arxiv.org/abs/1505.04597) arquitecture and pre-trained [EfficientNet](https://arxiv.org/abs/1905.11946) encoder. Early detection of polyps is crucial to prevent colorectal cancer, and applying computer vision techniques, such as image segmentation, has shown great potential in this area.

The model was trained using the public dataset [Kvasir-SEG](https://arxiv.org/abs/1911.07069), which contains 1000 colonoscopy images with their respective masks annotated by experts.

## Main Techniques and Tools
- U-Net: Convolutional neural network architecture for semantic segmentation.

- EfficientNet: Used as the encoder, with pre-trained weights to accelerate the training process.

- Kvasir-SEG Dataset: Public dataset with 1000 annotated images of gastrointestinal polyps.

- Transfer Learning: Used to improve accuracy and reduce training time.

- PyTorch: Deep learning framework used for implementation.

- Google Colab: Cloud computing platform used for training the models.

## Data
You can download and unzip the Kvasir-SEG data from [here](https://github.com/joliveiraas/kvasir-seg).

## HuggingFace Demo 🤗
Try out the [web demo](https://huggingface.co/spaces/joliveiraas/kvasir_polyp_seg) of this project! 
