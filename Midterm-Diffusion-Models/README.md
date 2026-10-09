# Midterm – Creating Images with Diffusion Models

**Course:** ITAI 2376  
**Team:** DataProxy  
**Dataset:** Fashion-MNIST

## Project Description

For this midterm project, Team DataProxy built and trained a diffusion model that learns how to generate clothing images using the Fashion-MNIST dataset. Fashion-MNIST contains 28×28 grayscale images across 10 clothing classes, including shirts, dresses, sneakers, bags, and ankle boots.

The project demonstrates the full diffusion process. We first add random noise to clean images at different timesteps, then train a U-Net neural network to predict the noise that was added. After training, the model starts with random noise and gradually removes it over multiple denoising steps to create a new image.

Our model includes a U-Net architecture with convolution blocks, downsampling, upsampling, skip connections, time embeddings, and class conditioning. We also used training and validation loss to track model performance and CLIP evaluation to compare generated images with their intended Fashion-MNIST classes.

During the project, we worked with:

- **60,000 Fashion-MNIST images**
- **48,000 training images**
- **12,000 validation images**
- **28×28 grayscale images**
- **10 clothing classes**
- **U-Net architecture**
- **100 diffusion steps**
- **MSE loss for noise prediction**
- **Class and time conditioning**
- **Training, validation, image generation, and CLIP evaluation**

## Project Files

[📓 View Completed Notebook](./completed-notebook/MD_Notebook_ElijahRaines_ITAI.pdf)

[📊 View Analysis Report](./analysis-report/MD_Report_ElijahRaines_ITAI.pdf)

[👥 View Contribution Journal](./contribution-journal/MD_DataProxy_ElijahRaines_Contribution_Journal_ITAI2376.pdf)

[💭 View Reflection Journal](./reflection-journal/MD_DataProxy_ElijahRaines_Reflection_Journal_ITAI2376.pdf)

## Team Members

- Elijah Raines
- Brandon Matias
- Justin Davis
- Jonah Joseph
- Fifehanmi Ogedengbe
- Samantha Mireles
