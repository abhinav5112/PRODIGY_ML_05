# Food Recognition & Calorie Estimation using Deep Learning

## Overview

This project is developed as **Task 5** of the **Prodigy InfoTech Machine Learning Internship**.

The objective of this project is to build a **Deep Learning-based Food Recognition System** capable of identifying food items from images and estimating their approximate calorie values.

The model is trained using **Transfer Learning with MobileNetV2** on the **Food-101 Dataset**, which contains 101 different food categories.

---

##Features

- Recognizes food from images
- Uses Transfer Learning with MobileNetV2
- Classifies images into **101 food categories**
- Estimates approximate calories
- Training & Validation Accuracy Visualization
- Training & Validation Loss Visualization
- Saves the best trained model automatically
- Predicts custom food images

---

## Dataset

**Dataset:** Food-101

- 101 Food Categories
- 101,000 Images
- Around 1,000 Images per Class

Download Dataset:

https://www.kaggle.com/datasets/dansbecker/food-101

---

## Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Project Structure

```
PRODIGY_ML_05/

│── dataset/
│── models/
│     ├── food_model.keras
│     └── final_food_model.keras
│
│── Food_Recognition.ipynb
│── calorie_mapping.py
│── predict.py
│── app.py
│── requirements.txt
│── README.md
│── .gitignore
```

---

## Installation

Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/PRODIGY_ML_05.git
```

Move into Project

```bash
cd PRODIGY_ML_05
```

Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Project

Train Model

```bash
python train.py
```

Predict Image

```bash
python predict.py
```

---

## Model Architecture

- MobileNetV2 (Pretrained on ImageNet)
- GlobalAveragePooling2D
- Dense Layer (512 Neurons)
- Dropout Layer
- Softmax Output Layer (101 Classes)

---

## Model Performance

Training Accuracy

- **41.13%**

Validation Accuracy

- **46.85%**

> **Note:** Accuracy can be further improved by increasing the number of epochs, fine-tuning MobileNetV2, and training on a GPU.

---

## Sample Prediction

**Input Image**

```
pizza.jpg
```

**Output**

```
Food Name : Pizza

Confidence : 96.7%

Estimated Calories : 285 kcal
```

---

## Learning Outcomes

- Deep Learning Fundamentals
- Computer Vision
- Image Classification
- Transfer Learning
- MobileNetV2
- Data Augmentation
- Model Training & Evaluation
- Calorie Estimation

---

## Future Improvements

- Real-Time Food Detection using Webcam
- Streamlit Web Application
- Mobile Deployment
- Nutrition Information
- Daily Calorie Tracking
- Meal Recommendation System

---

## Author

**Abhinav Kumar**

GitHub: https://github.com/abhinav5112

LinkedIn: www.linkedin.com/in/abhinavv-kumarr-5nov

---
If you found this project helpful, don't forget to give it a Star!
