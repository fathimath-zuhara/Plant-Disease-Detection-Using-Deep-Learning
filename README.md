# Plant Disease Detection Using Deep Learning

## Project Overview

This project focuses on automated plant disease detection using Deep Learning and Transfer Learning techniques. The system was developed using the PlantVillage dataset, which contains images of healthy and diseased plant leaves across 38 classes.

The goal of this project is to assist in early plant disease diagnosis by automatically classifying plant leaf images and identifying potential diseases.

## Dataset

**Dataset:** PlantVillage Dataset

**Total Classes:** 38

**Image Type:** RGB Color Images

The dataset contains images of healthy and diseased plant leaves from various crops and was used for training and evaluating deep learning models.

## Models Implemented

### MobileNetV2

* Transfer Learning Model
* Input Size: 128 × 128
* Validation Accuracy: **93.56%**
* Selected as Final Model

### EfficientNetB0

* Transfer Learning Model
* Used for performance comparison

## Data Preprocessing

* Image Resizing (128 × 128)
* Image Normalization
* Train-Validation Split
* Data Augmentation

  * Rotation
  * Zoom
  * Horizontal Flip
  * Width/Height Shift

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Learning Curves

### MobileNetV2 Performance

| Metric              | Value  |
| ------------------- | ------ |
| Validation Accuracy | 93.56% |
| Validation Loss     | 0.2075 |

MobileNetV2 outperformed EfficientNetB0 and was chosen as the final deployment model.

## Model Optimization

The final MobileNetV2 model was optimized using:

* TensorFlow Lite Quantization
* Model Size Reduction
* Inference Speed Evaluation

## Deployment

An interactive web application was developed using **Gradio**.

### Features

* Upload Plant Leaf Images
* Disease Prediction
* Confidence Score Display
* User-Friendly Interface


## 📷 Project Screenshots

### Learning Curve

![Learning Curve](screenshots/learning_curve.png)

### Confusion Matrix

![Confusion Matrix](screenshots/confusion_matrix.png)

### Classification Report

![Classification Report](screenshots/classification_report.png)

### Gradio Application

![Gradio Demo](screenshots/gradio_demo.png)

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Gradio
* TensorFlow Lite

## Project Structure

Plant-Disease-Detection/

├── PlantLeaf DL Project.ipynb

├── mobilenetv2_model.h5

├── plant_disease_model.tflite

├── README.md

├── requirements.txt

└── screenshots/

    ├── learning_curve.png

    ├── confusion_matrix.png

    ├── classification_report.png

    └── gradio_demo.png


## Future Improvements

* Use real-world agricultural datasets
* Improve classification of visually similar diseases
* Mobile application deployment
* Disease treatment recommendation system
* Cloud deployment for large-scale usage


## Author

**Fathimath Zuhara**

Master of Computer Applications (MCA)

Interested in Data Science, Machine Learning, Artificial Intelligence.

---

## Conclusion

This project demonstrates the effectiveness of Transfer Learning for plant disease detection. MobileNetV2 achieved a validation accuracy of 93.56% and was successfully optimized and deployed using Gradio. The solution can support early disease identification and contribute to smarter agricultural practices.
