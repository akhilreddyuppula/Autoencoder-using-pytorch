# Autoencoder-using-pytorch
PyTorch implementation of a Linear Autoencoder trained on MNIST — 
compresses 784-dimensional images into a 3-dimensional latent vector 
and reconstructs them using a symmetric decoder architecture.

Takes a 28×28 handwritten digit image, compresses it into just 3 numbers (latent vector), then reconstructs the original image from those 3 numbers — with no labels required.

Encoder (Compression):
784 → 128 → 64 → 12 → 3   ← latent vector

Decoder (Reconstruction):
3 → 12 → 64 → 128 → 784   ← reconstructed image

| Epoch | Loss |
|---|---|
| 1 | ~0.036 |
| 5 | ~0.032 |
| 10 | ~0.030 |

<img width="252" height="56" alt="epoch_0" src="https://github.com/user-attachments/assets/98b90292-ef95-488a-83de-5ab876012903" />

