# AI for Agriculture 

## Step1(Sara): Hyperspectral Preprocessing with PCA

### Reference Paper:
- Hyperspectral Image Classification using Deep Learning

### What I did:
- Loaded hyperspectral images (125 bands)
- Reshaped data for PCA
- Applied PCA to reduce dimensionality
- Reduced bands from 125 → 2
- Saved processed data

### Outputs:
- reduced_hs.npy
- sample_rgb.npy
- PCA visualization image

### Why PCA?
- Reduce complexity
- Keep important spectral information
- Improve model performance in next step
