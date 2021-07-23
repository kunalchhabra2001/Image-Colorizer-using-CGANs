# Image-Colorizer
This project is the implementation of a Conditional Generative adverserial network algorithm 

Model used is a CGAN network where input images are sketched versions of some colored pictures and model returns colored versions of the same
### Preprocessing

Original Dataset of CMP Facade Dataset had some 600 images, and we augment and normalize that to build 2000+ images

### Generation Model

Working on the UNet architecture for the generative model and hypertuning it

### Discriminator Model
Working on ConvNet architecture to cross verify the generative model

### Loss Function

The loss function I am using currently is the Sigmoid Cross-Entropy loss.

### Specs Used

Google Colab

### Reference Files

1. https://towardsdatascience.com/generative-adversarial-networks-gans-89ef35a60b69
