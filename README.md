# Facial Expression Recognition on FER2013 Dataset

This project implements a facial expression recognition model using a pre-trained ResNet50 on the FER2013 dataset. The model classifies facial expressions into 7 categories: angry, disgust, fear, happy, neutral, sad, and surprise.

## Dataset
- **FER2013**: Contains 35,887 grayscale 48x48 pixel images, split into training (28,709 images) and test (7,178 images) sets.
- The dataset is available on Kaggle: [FER2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013).

## Requirements
Install the required packages using:
```bash
pip install torch torchvision pandas numpy pillow matplotlib scikit-learn
