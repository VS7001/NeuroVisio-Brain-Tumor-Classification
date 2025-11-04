# 🧠 NeuroVision: MRI Brain Tumor Classification

**NeuroVision** is a deep learning–based AI system designed to detect and classify brain tumors from MRI scans.  
It uses **Convolutional Neural Networks (CNNs)** and **Grad-CAM visualization** to highlight affected regions, improving diagnostic accuracy and interpretability.

---

## 🎯 Objective

To build an intelligent, automated, and reliable system that can:
- Detect the presence of brain tumors.  
- Classify tumor types: **Glioma**, **Meningioma**, **Pituitary**, or **No Tumor**.  
- Visualize affected areas using **Grad-CAM** for clinical insight.

---

## 🧩 Features

- 🧠 Multi-class brain tumor classification  
- 🔥 Grad-CAM heatmap visualization  
- ⚙️ Built with **PyTorch** and **OpenCV**  
- 💻 Simple and fully local execution  
- 📈 High accuracy and model interpretability  

---

## 🧠 How It Works

1. MRI image is provided as input.  
2. The model processes it using a trained CNN.  
3. Prediction is generated (tumor type or no tumor).  
4. Grad-CAM highlights tumor regions for better understanding.

---

## 🧰 Technologies Used

| Category | Tools / Libraries |
|-----------|-------------------|
| **Language** | Python |
| **Framework** | PyTorch |
| **Libraries** | NumPy, OpenCV, Matplotlib, TorchVision, PIL |
| **Visualization** | Grad-CAM |
| **Environment** | Jupyter Notebook / VS Code |
| **Dataset Source** | Kaggle (Brain MRI Dataset) |

---
## 📸 Screenshots
### Upload Page
![Upload Page](screenshots/Upload page.png)

### Prediction Result
![Result Page](screenshots/Result page.png)
---

## ⚙️ How to Run the Project

Follow these steps to set up and execute the project 👇

### 1️⃣ Download the Project
📦 Download the full ZIP file from Google Drive:  
👉 [Download from Google Drive](https://drive.google.com/file/d/1qtZh3Rb9R1kAdVQi3pTSsG_YxlCCDcsN/view?usp=drive_link)

### 2️⃣ Extract the ZIP File
After downloading, **right-click → Extract All...**  
A folder named `NeuroVision` (or similar) will appear.

### 3️⃣ Open the Project Folder
Open the extracted folder in **VS Code** or **Jupyter Notebook**.

### 4️⃣ Install Required Dependencies
Run this command in the terminal:
```bash
pip install -r requirements.txt
```

### 5️⃣ Run the Application
To start the project, run:

```bash
python app.py
```

