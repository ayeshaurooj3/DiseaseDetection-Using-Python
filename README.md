# 🧠 Human Disease Detection Website

A comprehensive web-based AI application for detecting critical human diseases — **COVID-19**, **Pneumonia**, **Alzheimer’s Disease**, and **Brain Tumors** 
— using advanced deep learning models and medical imaging data. This platform is designed to assist healthcare professionals and patients with early, image-based diagnostics.

## 🌟 Key Features

- 🖼️ Upload medical images (X-ray, MRI) for automatic disease analysis
- ⚙️ Deep learning-based predictions using trained CNN models
- 📊 Detailed performance metrics: Accuracy, Precision, Recall, F1-Score
- 🧠 Multiple disease detection modules integrated into one platform
- 📱 User-friendly and responsive web interface
- 🔐 Optional user authentication system
- 🌐 Flask-powered web backend

## 🧬 Supported Disease Modules

| Disease        | Input Image Type | Model Used         | Output Labels                        |
|----------------|------------------|--------------------|---------------------------------------|
| COVID-19       | Chest X-ray      | CNN                | COVID / Normal / Viral Pneumonia     |
| Pneumonia      | Chest X-ray      | CNN                | Pneumonia / Normal                   |
| Alzheimer’s    | Brain MRI        | CNN                | Mild / Moderate / Severe             |
| Brain Tumor    | Brain MRI        | CNN                | Tumor Detected / Not Detected        |


## 🧰 Tech Stack

**Frontend:**
- HTML5, CSS3, Bootstrap
- JavaScript / jQuery

**Backend:**
- Python
- Flask Web Framework

**Machine Learning:**
- TensorFlow / Keras / PyTorch
- CNN
- OpenCV, NumPy, Pandas, Scikit-learn

**Deployment:**
- Flask Localhost (Development)

## 🗂️ Project Structure
human-disease-detection/
├── static/ # CSS, JS, image assets
├── templates/ # HTML pages (index, result, upload, etc.)
├── models/ # Trained model files (.h5 or .pt)
├── app.py # Main Flask server
├── library_command.txt(libraries that are required to code)

## 🧪 Datasets Used

- **COVID-19 X-ray Dataset** – [Kaggle Link](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database)
- **Pneumonia Chest X-ray Dataset** – [Kaggle Link](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- **Alzheimer’s MRI Dataset** – [Kaggle Link](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset)
- **Brain Tumor MRI Dataset** – [Kaggle Link](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

