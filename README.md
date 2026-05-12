# Image-Classification-of-Vehicles

# 🚗 Vehicle Image Classification using Logistic Regression

## 📌 Overview
This project is a Machine Learning based image classification system that classifies vehicle images into three categories:

- 🚘 Car
- 🏍️ Motorcycle
- 🛺 Autorickshaw

The model is trained using **Logistic Regression** with image preprocessing techniques such as resizing, grayscale conversion, normalization, and flattening.

The entire project was developed and tested in **Google Colab** using Python and Scikit-learn.

---

# 🧠 Features

✅ Image preprocessing pipeline  
✅ Automatic dataset ZIP extraction  
✅ Dynamic class detection  
✅ Grayscale image conversion  
✅ Logistic Regression classifier  
✅ Accuracy evaluation  
✅ Classification report  
✅ Confusion matrix visualization  
✅ Real-time image upload and prediction  
✅ Confidence score visualization  

---

# 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Matplotlib
- Pillow (PIL)
- Scikit-learn

---

# 📂 Dataset Structure

```text
dataset/
│
├── car/
├── motorcycle/
└── autorickshaw/
```

Each folder contains images belonging to that vehicle category.

---

# 📊 Dataset Details

- Approximately 50 images per class
- Small custom dataset
- Images resized to 64×64 pixels
- Grayscale preprocessing used for faster training

---

# ⚙️ Machine Learning Workflow

## 1️⃣ Data Preprocessing
- Resize images
- Convert to grayscale
- Normalize pixel values
- Flatten image arrays

## 2️⃣ Dataset Preparation
- Encode labels
- Split dataset into training and testing sets

## 3️⃣ Model Training
- Logistic Regression classifier
- Multi-class classification

## 4️⃣ Evaluation
- Accuracy score
- Classification report
- Confusion matrix

## 5️⃣ Prediction
- Upload custom image
- Predict vehicle class
- Display confidence scores

---

# 🎯 Model Accuracy

Example:

```text
Test Accuracy: 85%+
```

Accuracy may vary depending on dataset quality and image diversity.

---

# 📸 Sample Outputs

## Sample Dataset Images
(Add screenshot here)

## Confusion Matrix
(Add screenshot here)

## Prediction Results
(Add screenshot here)

---

# ▶️ How to Run

## Clone Repository

```bash
git clone https://github.com/your-username/vehicle-image-classification.git
```

## Install Dependencies

```bash
pip install scikit-learn pillow numpy matplotlib
```

## Run Notebook

Open the `.ipynb` notebook in:
- Google Colab
- Jupyter Notebook

Upload dataset ZIP file when prompted.

---

# 🔮 Future Improvements

- Implement CNN / Deep Learning
- Increase dataset size
- Add data augmentation
- Improve model accuracy
- Deploy as web application
- Real-time webcam detection

---

# 📚 Learning Outcomes

This project helped in understanding:

- Image preprocessing
- Machine Learning workflow
- Multi-class classification
- Logistic Regression
- Model evaluation techniques
- Computer Vision basics

---

# 👨‍💻 Author

Raj Chauhan

---

# ⭐ GitHub

If you found this project useful, consider giving it a ⭐ on GitHub.
