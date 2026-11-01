# Synthetic-Images-Generation-
This architecture combines an Attention-guided Conditional VAE with Latent Space SMOTE to balance datasets. An encoder maps masked inputs into a 256D latent space. Minority classes are oversampled by interpolating latent vectors via k-NN and decoding them. It optimizes using L1, Perceptual (LPIPS), and KL-divergence losses.
