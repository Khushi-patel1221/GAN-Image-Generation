## GAN-CelebA 👨‍🎤

GAN-CelebA is a Generative Adversarial Network project that generates realistic images of celebrities. The model is trained on the CelebA dataset, with the GAN architecture comprising a generator and a discriminator model trained in an adversarial setup. The goal is to create high-quality, synthetic celebrity images that are indistinguishable from real ones.

## Features 🎨

Generator and Discriminator Models: Includes both generator and discriminator architectures using convolutional layers.
Adversarial Training: Trains generator and discriminator in tandem, optimizing both models iteratively.
CelebA Dataset: Preprocessed celebrity images from the CelebA dataset resized to 64x64 pixels.
Image Generation: Generates synthetic images based on learned features from the dataset.
Evaluation and Visualization: Includes tools to visualize generated images and evaluate model performance.

## Technologies Used 💻

## Core Libraries:

Python: Core programming language used for model development.
TensorFlow/Keras: Framework used for building and training the GAN models.
NumPy: Used for data manipulation.
Matplotlib: Used for visualizing the generated images.
Dataset:CelebA: A large-scale dataset of celebrity faces, used to train the GAN

## Installation 🚀

Clone the repository:
1. Clone the repository:
```sh
git clone https://github.com/Khushi-patel1221/GAN-Image-Generation.git
cd GAN-Image-Generation
```

2.Set up the virtual environment
```sh
python3 -m venv gan-env
source gan-env/bin/activate  # For Linux/Mac
gan-env\Scripts\activate     # For Windows
```

3. Install dependencies:
```sh
pip install -r requirements.txt
```

4. Download CelebA dataset:

Visit CelebA Dataset to download the dataset.
Place the images in the dataset/ directory.

Outputs:

![](https://github.com/Khushi-patel1221/GAN-Image-Generation/blob/main/op1.jpeg)
![](https://github.com/Khushi-patel1221/GAN-Image-Generation/blob/main/op2.jpeg)
![](https://github.com/Khushi-patel1221/GAN-Image-Generation/blob/main/op3.jpeg)
![](https://github.com/Khushi-patel1221/GAN-Image-Generation/blob/main/op4.jpeg)
