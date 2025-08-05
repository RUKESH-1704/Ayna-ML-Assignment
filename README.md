# Ayna ML Assignment - Colored Polygon Generation using U-Net

## Objective
Train a U-Net model to generate a colored polygon image from a grayscale image and a given color name using PyTorch.

## Files
- `model.py` - U-Net model architecture.
- `Ayna_UNet_Assignment.ipynb` - Jupyter Notebook for training, validation, and visualization.
- `README.md` - This file.
- `Ayna_ML_Assignment_Report.pdf` - Summary report of the project.
- `sample_results/` - Folder with input, predicted, and ground truth images (optional).

## Setup Instructions
1. Clone the repository.
2. Install dependencies:
    ```bash
    pip install torch torchvision matplotlib wandb
    ```
3. Run the notebook: Ayna_UNet_Assignment.ipynb
    ```

## Notes
- Experiments are logged using Weights & Biases.
- Model supports dynamic input image sizes and works with 56 polygon samples provided.

## Author
Rukesh K
