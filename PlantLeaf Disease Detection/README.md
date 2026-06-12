# Plant Disease Detection Using Deep Learning

## Project Overview

This project develops an intelligent plant disease detection system using Deep Learning and Transfer Learning techniques on the PlantVillage dataset.

The objective is to automatically identify plant diseases from leaf images and assist farmers in early disease diagnosis.

---

## Dataset

* **Dataset:** PlantVillage
* **Total Classes:** 38
* **Image Type:** RGB Color Images

---

## Models Used

### MobileNetV2

* Transfer Learning
* Validation Accuracy: **93.56%**

### EfficientNetB0

* Used as a baseline model for comparison

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Optimization Techniques

* TensorFlow Lite (TFLite) Quantization
* Model Size Comparison
* Inference Speed Analysis

---

## Deployment

An interactive web application was developed using **Gradio**, allowing users to upload plant leaf images and receive disease predictions.

### Features

* Image Upload
* Disease Prediction
* Confidence Score Display
* User-Friendly Interface

---

## Results

MobileNetV2 achieved a validation accuracy of **93.56%** and was selected as the final deployment model.

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Gradio

---

## Project Structure

Plant-Disease-Detection/

├── Plant Disease Detection.ipynb

├── mobilenetv2_model.h5

├── plant_disease_model.tflite

├── requirements.txt

├── README.md

└── screenshots/

    ├── learning_curve.png

    ├── confusion_matrix.png

    └── gradio_demo.png

---

## Future Improvements

* Collect real-world agricultural datasets
* Improve prediction accuracy for visually similar diseases
* Deploy the model on mobile devices
* Integrate disease treatment recommendations

---

## Author

**Fathimath Zuhara**
