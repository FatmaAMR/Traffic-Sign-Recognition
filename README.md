# 🚦 Traffic Sign Classification (GTSRB)
![5909223852645403112](https://github.com/user-attachments/assets/9fdb34b8-4643-43a5-986c-d3d93dfc94c7)

---

## 📌 Project Overview
This project classifies **traffic signs** from the [GTSRB (German Traffic Sign Recognition Benchmark)]([https://benchmark.ini.rub.de/gtsrb_dataset.html](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign?select=Test) dataset.  
We built and compared two models:
- A **Custom CNN** trained from scratch.  
- A **MobileNet** model fine-tuned on the dataset.  

With an interactive **Gradio interface** where users can upload an image of a traffic sign and see predictions from both models.

---

## 🛠️ Technologies Used
- **Python 3.11**  
- **TensorFlow / Keras** (for deep learning models)  
- **OpenCV & PIL** (for image preprocessing)  
- **NumPy & Pandas** (data handling)  
- **Matplotlib & Seaborn** (visualization & confusion matrix)  
- **Gradio** (web-based interface for model inference)  
- **Kaggle Notebook** environment  


---

## 🚀 Features
- Preprocessing: Resize to **64x64**, normalization.  
- Model Training: CNN and MobileNet with data augmentation.  
- Evaluation: Accuracy, confusion matrix, validation split.  
- Deployment: Gradio-based interface inside Kaggle.  


