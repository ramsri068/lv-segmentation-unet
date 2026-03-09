# lv-segmentation-unet
Left ventricle segmentation using CAMUS dataset and U-Net

# Left Ventricle Segmentation using U-Net

## Project Overview
This project focuses on automatic segmentation of the left ventricle from echocardiography images using deep learning. The model is trained on the CAMUS dataset and uses the U-Net architecture to accurately segment cardiac structures.

The goal is to assist in medical image analysis by improving the efficiency and accuracy of heart chamber segmentation.

---

## Dataset
The project uses the CAMUS (Cardiac Acquisitions for Multi-structure Ultrasound Segmentation) dataset.

Dataset link:
https://www.creatis.insa-lyon.fr/Challenge/camus/

The dataset contains:
- Echocardiography images
- Ground truth segmentation masks
- Cardiac structure labels

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib
- Jupyter Notebook

---

## Model Architecture

This project uses the U-Net convolutional neural network for medical image segmentation.

Key features:
- Encoder-decoder architecture
- Skip connections
- Pixel-level prediction
- Suitable for biomedical segmentation tasks

---

## Project Structure

---

## Steps in the Project

1. Load and explore the CAMUS dataset
2. Preprocess ultrasound images
3. Build U-Net architecture
4. Train the model
5. Evaluate segmentation performance
6. Visualize predicted masks

---

## Evaluation Metrics

The model performance is evaluated using:

- Dice Coefficient
- Intersection over Union (IoU)
- Accuracy

---

## Results

The model successfully segments the left ventricle region from ultrasound images. Predictions closely match the ground truth masks.

---

## Future Improvements

- Hyperparameter tuning
- Data augmentation
- Training with larger datasets
- Experimenting with advanced segmentation models

---

## Author

Sriram Gowthaman  
Master’s in Artificial Intelligence  
University of West London
