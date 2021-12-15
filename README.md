# Deep Generative Models course, MIPT, 2021

## Description
The course is devoted to modern generative models (mostly in the application to computer vision). 

We will study the following types of generative models: 
- autoregressive models, 
- latent variable models, 
- normalization flow models, 
- adversarial models,
- diffusion models (sorry, next time).

Special attention is paid to the properties of various classes of generative models, their interrelationships, theoretical prerequisites and methods of quality assessment.

The aim of the course is to introduce the student to widely used advanced methods of deep learning.

The course is accompanied by practical tasks that allow you to understand the principles of the considered models.

## Materials

| Lecture | Date | Description | Lecture | Video |
|---------|------|-------------|---------|-------| 
| 0 | September, 8 | Intro. | [slides](lectures/intro.pdf) |  |
| 1 | September, 8 | Logistics. Motivation. Divergence minimization framework. Autoregressive modelling. | [slides](lectures/lecture1/Isachenko2021DeepGenerativeModels1.pdf) | [video](https://youtu.be/JfRkHnVtzeg) |
| 2 | September, 15 | Autoregressive models (MADE, WaveNet, PixelCNN, PixelCNN++). Bayesian Framework. | [slides](lectures/lecture2/Isachenko2021DeepGenerativeModels2.pdf) | [video](https://youtu.be/P2XTaPLUh2w) | 
| 3 | September, 22 | Latent Variable Models. Variational lower bound. EM-algorithm. Amortized inference. | [slides](lectures/lecture3/Isachenko2021DeepGenerativeModels3.pdf) | [video](https://youtu.be/m8pi9DybzCk) | 
| 4 | September, 29 | Reparametrization trick, Variational Autoencoder. Flow models definition. Forward and reverse KL divergence. | [slides](lectures/lecture4/Isachenko2021DeepGenerativeModels4.pdf) | [video](https://youtu.be/0rzj6uiENT4) | 
| 5 | October, 6 | Residual flows (Planar/Sylvester flows). Autoregressive flows (MAF/IAF/RealNVP). | [slides](lectures/lecture5/Isachenko2021DeepGenerativeModels5.pdf) | [video](https://youtu.be/vM55KpqYOZ8) | 
| 6 | October, 13 | Linear flows (Glow). Posterior collapse and decoder weakening. Tigher ELBO (IWAE). | [slides](lectures/lecture6/Isachenko2021DeepGenerativeModels6.pdf) | [video](https://youtu.be/0RUbgbMYMrY) |  
| 7 | October, 20 | ELBO surgery. VampPrior + flow-based VAE prior.  | [slides](lectures/lecture7/Isachenko2021DeepGenerativeModels7.pdf) | [video](https://youtu.be/Db_5chaA1jg) | 
| 8 | October, 27 | Flows-based VAE posterior vs prior. Uniform and variational dequantization. Disentanglement learning (beta-VAE). | [slides](lectures/lecture8/Isachenko2021DeepGenerativeModels8.pdf) | [video](https://youtu.be/epHEJBaS6og) | 
| 9 | Novermber, 10 | Disentanglement learning (DIP-VAE + summary). Likelihood-free learning. GAN theorem. | [slides](lectures/lecture9/Isachenko2021DeepGenerativeModels9.pdf) | [video](https://youtu.be/nMd2MwltiP4) | 
| 10 | Novermber, 17 | Vanishing gradients and Mode collapse. KL vs JSD. DCGAN. Wasserstein GAN. WGAN-GP. | [slides](lectures/lecture10/Isachenko2021DeepGenerativeModels10.pdf) | [video](https://youtu.be/l77WWHEMjwU) | 
| 11 | Novermber, 24 | Spectral Normalization GAN. f-divergence minimization. GAN evaluation (Inception score, FID). | [slides](lectures/lecture11/Isachenko2021DeepGenerativeModels11.pdf) | [video](https://youtu.be/QqaDzyMZsPg) | 
| 12 | December, 1 | GAN evaluation (Precision-Recall). GAN models (Self-Attention GAN, BigGAN, PGGAN, StyleGAN). Adversarial Variational Bayes. | [slides](lectures/lecture12/Isachenko2021DeepGenerativeModels12.pdf) | [video](https://youtu.be/a8-oOX0Pl5k) | 
| 13 | December, 15 | Neural ODE. Continuous-in-time NF (FFJORD). Discrete VAE (Gumbel-Softmax trick, VQ-VAE, VQ-VAE-2, DALL-E). | [slides](lectures/lecture13/Isachenko2021DeepGenerativeModels13.pdf) | [video](https://youtu.be/rNv8Szg-0Bw) | 


## Homeworks 
| Homework | Date | Deadline | Description | Link |
|---------|------|-------------|--------|-------|
| 1 | September, 15 | September, 26 | Theory: divergences + autoregressive models. Practice: MADE on 2D and MNIST. | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/hw1.ipynb) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2021-DGM-MIPT-course/blob/main/homeworks/hw1.ipynb)|
| 2 | September, 26 | October, 10 | Theory: log-derivative trick. Practice: PixelCNN on MNIST, VAE on 2D. | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/hw2.ipynb) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2021-DGM-MIPT-course/blob/main/homeworks/hw2.ipynb)|
| 3 | October, 10 | October, 24 | Theory: Sylvester flows. Practice: VAE on CIFAR10, RealNVP on 2D. | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/hw3.ipynb) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2021-DGM-MIPT-course/blob/main/homeworks/hw3.ipynb)|
| 4 | October, 24 | November, 14 | Theory: ELBO surgery MI. Practice: AF prior in VAE, AR Decoder. | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/hw4.ipynb) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2021-DGM-MIPT-course/blob/main/homeworks/hw4.ipynb)|
| 5 | November, 15 | November, 28 | Theory: IW dequantization, LSGAN. Practice: Standard GAN, WGAN, WGAN-GP. | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/hw5.ipynb) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2021-DGM-MIPT-course/blob/main/homeworks/hw5.ipynb)|
| 5 | November, 29 | December, 12 | Individual tasks. | |

## Game rules
- 6 homeworks each of 13 points = **78 points**
- oral cozy exam = **26 points**
- maximum points: 78 + 26 = **104 points**
### Final grade: `floor(relu(#points/8 - 2))`

## Previous episodes
- [OzonMasters, spring 2021](https://github.com/r-isachenko/2021-DGM-Ozon-course)
- [MIPT, autumn 2020](https://github.com/r-isachenko/2020-DGM-MIPT-course)

## Author, feel free to contact :)

- **telegram:** @roman_isachenko
- **e-mail:** roman.isachenko@phystech.edu
