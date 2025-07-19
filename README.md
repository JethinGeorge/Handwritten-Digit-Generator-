Handwritten Digit Generator using Variational Autoencoder (VAE)

This project implements a **Variational Autoencoder (VAE)** to generate realistic-looking handwritten digits, trained on the MNIST dataset. The model learns a latent representation of the digits and can generate new images by sampling from this latent space.

Project Overview

-  **Dataset**: MNIST (60,000 training images of handwritten digits)
-  **Model**: Variational Autoencoder (VAE)
-  **Goal**: Learn a compressed latent space from which new digits can be generated


##  Sample Output

<img width="790" height="790" alt="hw" src="https://github.com/user-attachments/assets/e02a0b8a-c958-44bb-8f5f-8fc16a382814" />



## Technologies Used

- Python 
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab


##  How to Run

1. Open the Colab notebook: `handwritten_digit_vae.ipynb`
2. Run all cells in order:
   - Load and normalize MNIST data
   - Build encoder and decoder networks
   - Train the VAE
   - Generate and visualize digits from random latent space

