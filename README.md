# Image-denoising-with-deep-learning
The comparison of CNN based and Fully Connected based Autoencoders.

This project aims to reduce the Additive White Gaussian Noise (AWGN) as much as possible while using minimum computing resources. Therefore, we have tried to keep the number of the parameters of the deep neural network models presented low. The models are derived and inspired from the papers [zhao](https://web.stanford.edu/class/cs331b/2016/projects/zhao.pdf) and [Tian et al](https://arxiv.org/pdf/1810.05052.pdf)
Furthermore, Thanks to Andrew NG and [deeplearning.ai](https://www.deeplearning.ai/) for the useful specializations and courses. We couldn't have done it without you!

**Our Models:**

Our models are separated into various kinds as follows:

    1. CNN based or Fully connected based autoencoder denoiser
    2. Using Adam or Gradient Descent Optimizer
    3. Using 3in3 or 5in5 filters (kernels) in the CNN based model
    4. Using symmetric or non-symmetric connection
    
These models are trained and validated on **two datasets**:
- SIMLEsmileD-master gray-scale 64in64 images (https://github.com/hromi/SMILEsmileD/archive)
- STL10 RGB 96in96 images (https://cs.stanford.edu/~acoates/stl10/)

**We have uploaded a sample notebook of our models in the repository, however, the rest of the models with the results are in two compressed files named after the dataset we used.**


# Authors: 

Kamyar Arshi (Kamyararshi@gmail.com) & Seyed Mohammad Mehdi Hosseini (Smmehdihosseini@gmail.com)
