Explore plant disease classification using Convolutional Neural Networks (CNNs) with PyTorch (From course at l'X ; Deep Learning).

The project uses the [PlantVillage Dataset](https://huggingface.co/datasets/geraldmc/plantvillage-full), which contains images of plant leaves across different health and disease categories.

Number of classes: 38

Training images: 43,356

Test images: 10,948

Total images: 54,304

Input image size: 256 × 256 pixels

Image format: RGB

The dataset provides separate training and test splits.

A simple custom four-stage CNN using PyTorch.

- Two successive 3 × 3 convolutional layers with padding to preserve spatial dimensions.

- Batch Normalization to stabilize and accelerate training.

- ReLU activation functions to introduce non-linearity.

- A 2 × 2 Max Pooling layer to progressively reduce spatial dimensions.

