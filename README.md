Handwritten Digit Generator using Variational Autoencoder (VAE)

This project implements a **Variational Autoencoder (VAE)** to generate realistic-looking handwritten digits, trained on the MNIST dataset. The model learns a latent representation of the digits and can generate new images by sampling from this latent space.

Project Overview

-  **Dataset**: MNIST (60,000 training images of handwritten digits)
-  **Model**: Variational Autoencoder (VAE)
-  **Goal**: Learn a compressed latent space from which new digits can be generated


##  Sample Output

<img src="generated_samples.png" width="500">



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


## File Structure

```plaintext
vae-handwritten-digit-generator
 ┣ 📄 README.md
 ┣ 📄 handwritten_digit_vae.ipynb
 ┗ 📷 generated_samples.png
