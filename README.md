# SuperResolution GAN (SRGAN)

# Overview
This repository gives a detailed way of implementing a Super-Resolution Generative Adversarial Network (SRGAN) for enhancing the quality of images. The network is trained using the Div2K dataset, and it's important to note that while you can achieve impressive results, the quality and accuracy of the generated images can be significantly improved with longer training time. The limitation of results may be due to limited computing resources and training time constraints. 

The GAN network was constructed by referring to the generator and discriminator architecture diagram in the paper: 
**"Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network"**

# Prerequisites
Before you begin implementing the SRGAN, make sure you have the following prerequisites in place:

Python 3.x
TensorFlow 
NumPy
CUDA-enabled GPU (strongly recommended for faster training)

** P.S. - Limitation of GPU limits quality of results **  
