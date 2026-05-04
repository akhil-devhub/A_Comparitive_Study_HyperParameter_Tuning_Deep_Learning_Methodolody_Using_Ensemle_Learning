# 🧠 A Comparative Study and Hyperparameter Tuning DL Methodology Using Ensemble Learning

This capstone project presents an automated deep learning pipeline that simplifies the process of model selection, hyperparameter tuning, and evaluation using **Optuna** and **Streamlit**. The system supports multiple CNN architectures (ResNet50, VGG16, MobileNetV2, DenseNet121) and offers an intuitive UI for both structured and unstructured datasets.

---

## 🚀 Project Overview

Training deep learning models often requires expertise and time, especially when it comes to **CNN architecture selection** and **hyperparameter tuning**. This project aims to **democratize deep learning** through:

- **Automated model generation** and training  
- **Real-time evaluation metrics**  
- **No-code user interface**

Built using:
- 🧪 **Optuna** for hyperparameter optimization  
- 🖼️ **Streamlit** for UI  
- 📦 Support for both **CSV** and **image ZIP** datasets

---

## 🎯 Objectives & Deliverables

### ✅ Objectives
- Automate CNN model selection and tuning  
- Provide real-time training feedback and metrics  
- Support various dataset types (structured/unstructured)  

### 📦 Deliverables
- Streamlit Web App with upload + visualization  
- Optuna Tuner with CNN comparison  
- Evaluation Dashboard showing Accuracy, Precision, Recall, F1 Score, and Confusion Matrix  

---

## 🧱 System Architecture

```
User Upload → Preprocessing → Model Generator → Optuna Hyperparameter Tuner → CNN Training → Evaluation → UI Output
```

### Modules:
1. **Data Ingestion:** Supports `.csv` and `.zip` inputs  
2. **Preprocessing:** Image resizing, label encoding, one-hot encoding  
3. **Model Generator:** Selects CNN model (ResNet50, VGG16, MobileNetV2, DenseNet121)  
4. **Hyperparameter Tuner:** Optimizes via Optuna  
5. **Evaluation:** Computes accuracy, precision, recall, F1 score  
6. **UI:** Interactive web app built with Streamlit  

---

## ⚙️ Hyperparameter Tuning (Optuna)

- **Optimizers:** `adam`, `sgd`, `rmsprop`  
- **Activations:** `relu`, `tanh`  
- **Other Parameters:** Batch size, Epochs (user-controlled via slider)  
- **Search Method:** Tree-structured Parzen Estimator (TPE)  

Each trial returns:
- Best CNN model  
- Best hyperparameters  
- Evaluation scores  

---

## 📊 Evaluation Metrics

- **Accuracy** = Correct predictions / Total samples  
- **Precision** = TP / (TP + FP)  
- **Recall** = TP / (TP + FN)  
- **F1 Score** = 2 × (Precision × Recall) / (Precision + Recall)  
- **Confusion Matrix:** Shown using Streamlit table  

---

## 🖥️ UI Features

- Upload structured `.csv` or image `.zip`  
- Choose epochs and batch size via sliders  
- Click "Train Model" to initiate training  
- View best model, hyperparameters, and evaluation results  

---

## 📌 Results

- **Optuna** efficiently selected the best model and configuration.  
- Models trained with early stopping to avoid overfitting.  
- Real-time performance metrics enabled quick experimentation.  

![image](https://github.com/user-attachments/assets/cdc6a6dc-25ad-4799-b7f3-1e0e000202f0)

![image](https://github.com/user-attachments/assets/3ec217eb-4735-4889-8c9e-2b256698df2b)

---

## ✅ Conclusion & Social Impact

- Brings automation, accessibility, and reproducibility to deep learning.  
- Reduces technical barrier—ideal for education, prototyping, and research.  
- Enables both technical and non-technical users to experiment with CNNs.  

---

## 🧰 Technologies Used

- Python 🐍  
- TensorFlow / Keras  
- Streamlit 🌐  
- Optuna 🔍  
- Pandas, NumPy, Scikit-learn  
- OpenCV  

---

## ✍️ Authors

- **Ganesh Sesha Sai Akhil Koutarapu**   
- **Venkatesh Komalli**  
- **Venkata Arun Kumar Perla**  
- **Guide:** Dr. Ashu Abdul  

---

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

Special thanks to **SRM University – AP** and our guide **Dr. Ashu Abdul** for their continuous support and mentorship throughout the project.

📚 **Publication Highlight:**  
We are proud to have published a book chapter titled  
**“Harnessing AI and Predictive Analytics for Competitive Decision-Making”**  
with **IGI Global**, further reinforcing the practical relevance of our project work.

---

