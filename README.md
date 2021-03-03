# Image-denoising-with-deep-learning
The comparison of CNN based and Fully Connected based Autoencoders
This project aims to reduce the additive White Gaussian Noise (AWGN) as much as possible, while using minimum computing resource. Therefore, we have tried to keep the number of the parameters of the deep neural network models presented low. The models are derived and inspired from the papers [**Zhao**](https://web.stanford.edu/class/cs331b/2016/projects/zhao.pdf) and [**Tian et al**](https://arxiv.org/pdf/1810.05052.pdf) Furthermore, thanks to **Andrew NG** and [deeplearning.ai](deeplearning.ai) for the usefull specializations and courses. We couldn't have done it without you!

Our Models:

Our models are sepperated into various kinds as follows:

1. CNN based or Fully connected based denoiser Autoencoder
2. Using Adam or Gradient Decent Optimizer
3. Using 3in3 or 5in5 filters (kernels) in the CNN based model
4. Using a symmetric or non-symmetric connetion



These models are trained and tested on two data sets:

SIMLEsmileD-master gray-scale 64in64 images (https://github.com/hromi/SMILEsmileD/archive)
STL10 RGB 96in96 images (https://cs.stanford.edu/~acoates/stl10/)

**We have uploaded a samle notebook of our models in the repository, however, the rest of the models with the results are in two compressed files named after the dataset we used.**


# Authors: 

**Kamyar Arshi** (kamyararshi@gmail.com) & **Seyed Mohammad Mehdi Hosseini** (smmehdihosseini@gmail.com)
