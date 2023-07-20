# RBM (Restricted Boltzmann Machine) Example

This repository contains an example implementation of a Restricted Boltzmann Machine (RBM) using TensorFlow. The RBM is trained on the MNIST dataset for image reconstruction.

## Overview

The `RBM` class is implemented with methods for training the RBM, reconstructing input data, and generating output. It utilizes Gibbs sampling with Contrastive Divergence for training. The RBM architecture consists of a visible layer and a hidden layer with binary units.

## Dependencies

The code requires the following libraries:

- TensorFlow
- NumPy
- Matplotlib

## Usage
 Clone the repository and navigate to the project directory.
```bash
git clone https://github.com/pyritez3/DL-RBM.git

cd DL-RBM
```

You can install the dependencies using the following command:

```bash
pip install tensorflow numpy matplotlib
```

## Results

The script will train the RBM for a specified number of epochs and plot the reconstruction error over epochs. Additionally, it will show a comparison of original and reconstructed images using random samples from the test data.

## Customize

You can modify the hyperparameters such as learning rate, batch size, number of hidden units, and training epochs by changing the corresponding values in the RBM class instantiation (rbm = RBM(...)) and the train method call (rbm.train(...)).

Feel free to experiment with different configurations and datasets to explore the capabilities of RBMs.

## License

This project is licensed under the MIT License

