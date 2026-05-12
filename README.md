# Deep Learning Image Classification Project

## Overview

This project compares multiple deep learning approaches for image classification using transfer learning and feature extraction techniques.

The notebook evaluates and compares:

* EfficientNet-B0 + SVM
* ResNet50 + SVM
* EfficientNet-B0 End-to-End Training
* ResNet50 End-to-End Training

The project focuses on measuring:

* Accuracy
* Precision
* Recall
* F1-Score
* Training and execution time

---

## Technologies Used

* Python
* TensorFlow / Keras
* TensorFlow Datasets
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Models Used

### 1. EfficientNet-B0 + SVM

Features are extracted using EfficientNet-B0 pretrained on ImageNet, then classified using an SVM classifier.

### 2. ResNet50 + SVM

Features are extracted using ResNet50 pretrained on ImageNet, then classified using an SVM classifier.

### 3. EfficientNet-B0 End-to-End

EfficientNet-B0 is fine-tuned directly for classification using a neural network output layer.

### 4. ResNet50 End-to-End

ResNet50 is fine-tuned directly for classification using a neural network output layer.

---

## Project Structure

```bash
├── notebookdeep66.ipynb
├── results_all_models.csv
├── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

Install dependencies:

```bash
pip install tensorflow tensorflow-datasets numpy pandas matplotlib seaborn scikit-learn
```

---

## Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then run:

```bash
notebookdeep66.ipynb
```

---

## Features

* Transfer learning using pretrained CNN models
* Feature extraction using deep learning architectures
* SVM classification
* End-to-end neural network training
* Comparative performance analysis
* Automatic result export to CSV
* Visualization and evaluation metrics

---

## Evaluation Metrics

The following metrics are used to compare models:

* Accuracy
* Precision
* Recall
* F1-Score
* Execution Time

---

## Output

The notebook generates:

* Trained models
* Evaluation reports
* Confusion matrices
* Comparative analysis tables
* `results_all_models.csv`

---

## Example Libraries Imported

```python
import tensorflow as tf
import tensorflow_datasets as tfds
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.svm import SVC
from tensorflow.keras.applications import EfficientNetB0, ResNet50
```

---

## Future Improvements

* Add more pretrained models
* Hyperparameter tuning
* Deploy model using Flask or Streamlit
* Add real-time prediction interface
* Train on larger datasets

---

## License

This project is for educational and academic purposes.
