# Autoencoder Variants: A Comparative Study
This project explores the performance of three Autoencoder architectures for image compression: a simple Autoencoder, a Convolutional Autoencoder, and a Variational Autoencoder. The evaluation is performed using objective metrics (PSNR, SSIM) and subjective visual assessments of the reconstructed images.

# 1. Autoencoder
**Description:**
A basic Autoencoder architecture trained with a mean squared error (MSE) loss function.

**Evaluation:**

- Rate-Distortion Tradeoff: Assessed by varying latent sizes.
- Objective Metrics: Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index Measure (SSIM).
- Subjective Evaluation: Reconstructed images are plotted alongside the original images for visual comparison.
# 2. Convolutional Autoencoder
**Description:**
A Convolutional Autoencoder designed to leverage convolutional layers for capturing spatial dependencies in images. Trained with an MSE loss function.

**Evaluation:**

- Rate-Distortion Tradeoff: Investigated across different latent sizes.
- Objective Metrics: PSNR and SSIM scores calculated for reconstructed images.
- Subjective Evaluation: Visual comparison by plotting reconstructed images versus originals.
# 3. Variational Autoencoder
**Description:**
A Variational Autoencoder (VAE) that encodes images into a probabilistic latent space, adding a regularization term to the loss function.

**Evaluation:**

-Subjective Evaluation: Visual inspection of reconstructed images by juxtaposing them with the original inputs.
