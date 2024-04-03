# Brain Tumor Detection & Image Generation

This project aims to detect brain tumors in scanned MRI images using convolutional neural networks (CNNs) like RESNET50, InceptionV3, EfficientNet, and VGG16. Additionally, it includes a Generative Adversarial Network (GAN) based approach to generate brain tumor scanned MRI images.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [License](#license)

## Introduction

Brain tumors are a serious medical condition that require accurate and timely diagnosis. This project utilizes deep learning techniques to assist in the detection of brain tumors from MRI scans, providing a potentially faster and more efficient method of diagnosis.

## Installation

To run this project locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Download the pre-trained weights for the CNN models (RESNET50, InceptionV3, EfficientNet, VGG16).
4. Ensure you have the necessary hardware requirements for running the GAN model.

## Usage

Once installed, you can use the provided scripts to:

- Train the CNN models on your own dataset.
- Evaluate the performance of the trained models on test data.
- Generate synthetic brain tumor MRI images using the GAN model.

Refer to the documentation within each script for detailed usage instructions.

## Models

### Convolutional Neural Networks (CNNs)

- RESNET50
- InceptionV3
- EfficientNet
- VGG16

### Generative Adversarial Network (GAN)

- Deep Convolutional GAN (DCGAN)

## License

This project is licensed under [The Unlicense](https://unlicense.org/) - see the [LICENSE](LICENSE) file for details.
