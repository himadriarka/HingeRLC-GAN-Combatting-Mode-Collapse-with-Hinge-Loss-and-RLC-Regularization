# HingeRLC-GAN-Combatting-Mode-Collapse-with-Hinge-Loss-and-RLC-Regularization
**Overview**
HingeRLC-GAN is a novel Generative Adversarial Network (GAN) architecture designed to address mode collapse by enhancing the diversity and stability of generated data. The project introduces Hinge Loss and Regularized Loss Control (RLC) as key components to improve training stability and output diversity, particularly in small datasets.

**Features**
Hinge Loss: Used to provide smoother gradient flow and mitigate vanishing gradients during training, contributing to more stable GAN training.
Regularized Loss Control (RLC): A regularization technique that penalizes large gradient updates, helping to control overfitting and promote better generalization.
ResNet-based Architecture: The generator and discriminator networks are constructed using ResNet blocks for improved image quality and mode coverage.
Improved Mode Diversity: HingeRLC-GAN achieves up to 30% better mode coverage compared to other GAN variants.
Results
**FID Score**: 18
**KID Score**: 0.001
Our model outperforms baseline models like DCGAN, LSGAN, and DRAGAN in terms of mode diversity and training stability.
Project Structure
src/: Contains the implementation of the HingeRLC-GAN model, including generator and discriminator architectures.
data/: A directory for storing the dataset used for training the GAN.
experiments/: Code for running different experiments and evaluations on the model.
models/: Saved model weights and checkpoints.
README.md: This file, providing an overview of the project.

**Dataset**
The model was trained and evaluated using the CIFAR-10 dataset. However, it is designed to work with other image datasets, provided they are preprocessed into the required format.
