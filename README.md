
# Hyperspectral Image Classification with 1-D, 2-D, 3-D, and Hybrid CNNs

## Project Overview
This project focuses on the **classification of hyperspectral satellite images** using various types of Convolutional Neural Networks (CNNs). The goal is to implement and compare **1-D, 2-D, 3-D**, and **hybrid CNN models** to identify the most efficient method for accurate hyperspectral image classification.

### Files Overview:
- **HyperspectralClassification1D**: Jupyter Notebook implementing 1-D CNN.
- **HyperspectralClassification2D**: Jupyter Notebook implementing 2-D CNN.
- **HyperspectralClassification3D**: Jupyter Notebook implementing 3-D CNN.
- **HyperspectralClassificationHybrid**: Jupyter Notebook implementing hybrid CNN combining 1-D, 2-D, and 3-D techniques.
- **Pavia_gt**: Ground truth data for the Pavia hyperspectral dataset.
- **Pavia**: The hyperspectral dataset from Pavia, used for training and evaluation.

## Project Structure
- **Data**: The dataset used is the **Pavia** hyperspectral image data, including both the image data and corresponding ground truth labels (`Pavia_gt`).
- **Models**:
  - **1-D CNN**: A convolutional model that processes each spectral band independently for classification.
  - **2-D CNN**: Uses spatial features from 2D patches of the hyperspectral images.
  - **3-D CNN**: Leverages both spectral and spatial features by applying 3D convolutions.
  - **Hybrid CNN**: Combines elements of 1-D, 2-D, and 3-D CNNs to benefit from the strengths of each approach.

## Objective
The objective of this project is to evaluate the performance of different CNN architectures in classifying hyperspectral images and to determine which approach is best suited for this type of data. 

## Installation & Usage
1. **Data Preparation**: Ensure the Pavia dataset (`Pavia` and `Pavia_gt`) is loaded and accessible.
2. **Running Notebooks**: Use the provided Jupyter Notebooks to explore each model:
   - `HyperspectralClassification1D.ipynb`
   - `HyperspectralClassification2D.ipynb`
   - `HyperspectralClassification3D.ipynb`
   - `HyperspectralClassificationHybrid.ipynb`
3. **Training and Evaluation**: Each notebook allows you to train and test a model on the Pavia dataset.

## Key Steps:
1. **Data Preprocessing**: Normalize and prepare the hyperspectral data.
2. **Model Implementation**: Implement the four CNN architectures.
3. **Training**: Train each model using the Pavia dataset.
4. **Evaluation**: Compare models based on accuracy, precision, recall, and F1 score.

## Conclusion
After training and evaluating the models, the project will determine which CNN architecture—1-D, 2-D, 3-D, or hybrid—offers the best performance for hyperspectral image classification tasks.

## Future Work
- Further tuning of hyperparameters.
- Exploration of additional architectures such as transformers or other deep learning models.

##Contact : 
Alidor Mbaya : mbayandjambealidor@gmail.com
