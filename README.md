# 🚢 Ship Segmentation using Deep Learning

This project focuses on segmenting ships in satellite images using Convolutional Neural Networks (CNNs) and semantic segmentation techniques. The model takes in satellite images and predicts masks highlighting ship locations.

## 📁 Project Structure

- `ship_segmentation.ipynb` — The main Jupyter notebook containing:
  - Data preprocessing and visualization
  - U-Net model architecture for segmentation
  - Model training and evaluation
  - Prediction visualization on test images

## 🧠 Model Architecture

The notebook uses a U-Net based CNN for semantic segmentation. The U-Net is designed to perform pixel-wise classification to differentiate ship pixels from background pixels in high-resolution satellite imagery.

## 📊 Dataset

- The dataset likely consists of satellite images with corresponding binary masks (ships vs background).
- Data preprocessing includes:
  - Image resizing
  - Mask preparation
  - Normalization
- Augmentations may be applied to improve generalization.

> 📌 If you're using a specific dataset (e.g., Airbus Ship Detection from Kaggle), make sure to include a download link or instructions for access.

## ⚙️ Tech Stack

- Python
- TensorFlow / Keras or PyTorch (based on the notebook)
- OpenCV / PIL
- NumPy, Pandas
- Matplotlib / Seaborn

## 🏁 How to Run

1. Download the notebook (`ship_segmentation.ipynb`).
2. Open it using [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Make sure the required packages are installed.
4. Run all the cells step-by-step to see the results.
