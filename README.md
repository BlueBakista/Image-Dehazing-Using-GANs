# Deep Learning Project

## Overview
This project involves training a deep learning model for image processing using PyTorch. The dataset is downloaded and preprocessed for training and validation.

## Environment Setup
The dataset is downloaded using Google Drive and extracted before training begins.

## Dependencies
The following Python libraries are required:
```bash
pip install torch torchvision numpy tqdm pillow skimage
```

## Model Training
- The model is trained using PyTorch on GPU (if available).
- Loss functions used:
  - **Binary Cross-Entropy Loss (BCEWithLogitsLoss)**
  - **L1 Loss**
- Training parameters:
  - **Learning Rate:** 2e-4
  - **Batch Size:** 16
  - **Image Size:** 256x256
  - **Epochs:** 35

## Dataset
- **Training Data Path:** `/content/final_dataset/train`
- **Validation Data Path:** `/content/final_dataset/val`

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```bash
   python train.py
   ```

## Checkpoints
- Model weights are stored at `/content/drive/MyDrive/Weights`

## Contributors
- Prasoon Narayan Singh

## License
This project is licensed under the MIT License.

