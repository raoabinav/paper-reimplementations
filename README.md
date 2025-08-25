# Deep Learning Paper Reimplementations

This repository contains my implementations of influential deep learning papers, focusing on computer vision and generative models. Each implementation is done in PyTorch and includes Jupyter notebooks with detailed explanations and training procedures.

## Implemented Papers

### 1. AlexNet (2012)
- **Paper**: [ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)
- **Notebook**: [AlexNet.ipynb](AlexNet.ipynb)
- **Key Contribution**: Pioneering work that popularized deep convolutional neural networks for image classification.

### 2. VGG (2015)
- **Paper**: [Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556)
- **Notebooks**: 
  - [VGG16.ipynb](VGG16.ipynb)
  - [VGG16_deconv.ipynb](VGG16_deconv.ipynb) (with deconvolutional visualization)
- **Key Contribution**: Demonstrated that network depth is crucial for better performance.

### 3. ResNet (2015)
- **Paper**: [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)
- **Notebook**: [ResNET50.ipynb](ResNET50.ipynb)
- **Key Contribution**: Introduced residual connections to enable training of very deep networks.

### 4. All Convolutional Net (2015)
- **Paper**: [Striving for Simplicity: The All Convolutional Net](https://arxiv.org/abs/1412.6806)
- **Notebook**: [TheAllConvNet_StrivingForSimplicity.ipynb](TheAllConvNet_StrivingForSimplicity.ipynb)
- **Key Contribution**: Showed that max-pooling can be replaced by convolutional layers with stride.

### 5. Progressive GAN (2018)
- **Paper**: [Progressive Growing of GANs for Improved Quality, Stability, and Variation](https://arxiv.org/abs/1710.10196)
- **Notebook**: [Progressive_GAN.ipynb](Progressive_GAN.ipynb)
- **Key Contribution**: Introduced progressive growing of GANs for higher resolution image generation.

### 6. StyleGAN (2019)
- **Paper**: [A Style-Based Generator Architecture for Generative Adversarial Networks](https://arxiv.org/abs/1812.04948)
- **Notebook**: [StyleGAN.ipynb](StyleGAN.ipynb)
- **Key Contribution**: Introduced style-based generator for better control over generated images.

### 7. StyleGAN2 (2020)
- **Paper**: [Analyzing and Improving the Image Quality of StyleGAN](https://arxiv.org/abs/1912.04958)
- **Notebook**: [StyleGAN2_Round1.ipynb](StyleGAN2_Round1.ipynb)
- **Key Contribution**: Improved image quality and fixed artifacts in StyleGAN.

### 8. ZCA Whitening
- **Notebook**: [ZCA_Transform.ipynb](ZCA_Transform.ipynb)
- **Purpose**: Data preprocessing technique for whitening image data.

### 9. Basic Convolutional Networks
- **Notebook**: [basic_convolution.ipynb](basic_convolution.ipynb)
- **Purpose**: Fundamental CNN implementations and experiments.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/paper-reimplementations.git
   cd paper-reimplementations
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Each notebook is self-contained and can be run independently. Open any notebook with Jupyter Lab or Jupyter Notebook to explore the implementation and run the code.

## Dependencies

- Python 3.8+
- PyTorch
- Jupyter Lab/Notebook
- Other dependencies are listed in `requirements.txt`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
