# GANS for MNIST Dataset

This repository contains the implementation of Generative Adversarial Networks (GANs) for the MNIST dataset. GANs are a class of machine learning models that are used for generating new data samples that resemble a given training dataset.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we explore the use of GANs to generate realistic handwritten digits from the MNIST dataset. GANs consist of two neural networks, a generator and a discriminator, that compete against each other in a game-theoretic framework. The generator tries to generate realistic samples, while the discriminator tries to distinguish between real and generated samples.

## Installation

To run this project, you need to have Python 3.x and the following dependencies installed:

- PyTorch
- NumPy
- Matplotlib

You can install the required dependencies by running the following command:

```
pip install -r requirements.txt
```

## Usage

To train the GAN model on the MNIST dataset, run the following command:

```
python train.py
```

After training, you can generate new samples using the trained model by running the following command:

```
python generate_samples.py
```

## Contributing

Contributions are welcome! If you have any ideas or suggestions to improve this project, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
