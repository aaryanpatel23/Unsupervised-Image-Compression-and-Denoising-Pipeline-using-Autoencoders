# Fashion-MNIST Autoencoder

This repository contains a TensorFlow/Keras implementation of:
- An undercomplete autoencoder with latent sizes 8, 32, and 64.
- A denoising autoencoder trained on noisy images with clean targets.
- Test-set MSE evaluation, theoretical value-count compression ratios, loss curves, and image visualizations.

## Run
1. Open `fashion_mnist_autoencoder.ipynb` in Google Colab or Jupyter.
2. Install dependencies if needed: `pip install tensorflow matplotlib numpy`
3. Run all cells from top to bottom. Fashion-MNIST is downloaded automatically by Keras.
4. Copy the measured MSE values and generated plots into `report.pdf` or update the report with your actual run results.

## Notes
The compression ratio shown is `784 / latent_size`. It compares the number of pixel values with the number of latent values and excludes model weights and storage overhead. Results can vary by training environment and random initialization.
