**🥬 Vegetable Image Classifier using CNN**
An AI-powered deep learning project that classifies vegetable images using a Convolutional Neural Network (CNN).  
The system is capable of identifying different vegetables from uploaded images and provides real-time predictions through a Streamlit web application.

**📌 Project Overview**
This project uses **Computer Vision** and **Deep Learning** techniques to classify vegetable images into different categories.  
A CNN model was trained on a custom vegetable image dataset and deployed using **Streamlit** for an interactive user experience.

The application allows users to:
- Upload vegetable images
- Predict vegetable class instantly
- View prediction confidence score
- Store prediction history (MongoDB integration)

# 🧠 Classes Used
The model classifies the following vegetable categories:
- 🌶 Green Chili
- 🥒 Pointed Gourd
- 🫛 Green Peas
- 🥬 Ivy Gourd
- 🥗 Ladyfinger (Okra)

**⚙️ Technologies Used**
| Technology | Purpose |
|---|---|
| Python | Core programming language |
| TensorFlow / Keras | CNN model development |
| OpenCV | Image processing |
| NumPy | Numerical computations |
| Pandas | Data handling |
| Matplotlib | Visualization |
| Streamlit | Web application deployment |
| MongoDB | Database integration |

**🏗 System Architecture**
The workflow of the project follows these stages:

**1️⃣ Dataset Collection**
Vegetable image dataset containing multiple images of:
- Green Chili
- Pointed Gourd
- Ladyfinger (Okra)
- Green Peas
- Ivy Gourd

**2️⃣ Data Preprocessing**
The dataset undergoes preprocessing before training:
- Image resizing to **128×128**
- Pixel normalization
- Data augmentation
- Train/Validation/Test split

**3️⃣ CNN Model Training**
The Convolutional Neural Network architecture includes:
- Input Layer
- Conv2D + ReLU
- MaxPooling Layer
- Conv2D + ReLU
- MaxPooling Layer
- Flatten Layer
- Dense Layer
- Dropout Layer
- Softmax Output Layer

**4️⃣ Model Evaluation**
The trained model is evaluated using:
- Accuracy
- Loss
- Confusion Matrix
- Validation Performance

**5️⃣ Model Saving**
The trained model is saved as:
```python
vegetable_model.keras

**6️⃣ Streamlit Deployment**
The Streamlit web application provides:
- Image upload interface
- Real-time vegetable prediction
- Confidence score display
- User-friendly AI interface

**📂 Project Structure**
```bash
Vegetable_Classifier/
│
├── app.py
├── vegetable_classifier.py
├── data_preprocessing.py
├── data_augmentation.py
├── requirements.txt
├── vegetable_model.keras
│
├── raw_dataset/
├── balanced_dataset/
├── augmented_dataset/
│
└── README.md

---

▶️ Run the Project
Start the Streamlit application using:
streamlit run app.py

📊 Model Performance
The CNN model achieves strong classification performance on the validation dataset.
Evaluation metrics include:
- Training Accuracy
- Validation Accuracy
- Loss Curves
- Confusion Matrix

📸 Application Features
✅ Upload vegetable images  
✅ Real-time prediction  
✅ Confidence score display  
✅ Deep learning based classification  
✅ Streamlit interactive UI  
✅ MongoDB integration support  
ve web application to provide a complete end-to-end intelligent classification system.

---
