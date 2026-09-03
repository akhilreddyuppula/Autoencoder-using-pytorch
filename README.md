# Autoencoder (PyTorch)

An autoencoder built in PyTorch that compresses an image into a compact latent vector and reconstructs it. A foundational unsupervised-learning project demonstrating representation learning and dimensionality reduction.

## What It Does

- **Encoder** compresses the input image into a lower-dimensional latent vector.
- **Decoder** reconstructs the original image from that latent vector.
- The network learns, without labels, to capture the most important features needed to rebuild its input.

## Tech Stack

Python, PyTorch



## Notes / Future Improvements

- Compare reconstruction quality across different latent vector sizes.
- Extend to a denoising autoencoder (reconstruct clean images from noisy inputs).
- This project pairs naturally with the Variational Autoencoder repo — the VAE extends this idea to a probabilistic latent space.



| Epoch | Loss |
|---|---|
| 1 | ~0.036 |
| 5 | ~0.032 |
| 10 | ~0.030 |

<img width="252" height="56" alt="epoch_0" src="https://github.com/user-attachments/assets/98b90292-ef95-488a-83de-5ab876012903" />

