# 🎗️ Breast Cancer Predictor

![GitHub Stars](https://img.shields.io/github/stars/your-repo.svg?style=social)
![GitHub Forks](https://img.shields.io/github/forks/your-repo.svg?style=social)
![GitHub License](https://img.shields.io/github/license/your-repo)

## 📌 Overview
The **Breast Cancer Predictor** is a machine learning-powered web app built using **Streamlit**. It predicts whether a breast mass is **benign** or **malignant** based on cytology measurements. The app assists medical professionals in preliminary diagnosis using a trained **Logistic Regression model**.

## 🚀 Features
✅ **Interactive Sliders** – Users can input cell nucleus measurements.  
✅ **Radar Chart Visualization** – Compares mean, standard error, and worst values.  
✅ **Machine Learning Model** – Predicts cancer type with probability scores.  
✅ **Custom Styling** – Designed with CSS for a modern UI.  

## 🖼️ Screenshot
### 🔹 Dashboard View & Predictions
![Breast Cancer Predictor]![Screenshot (53)](https://github.com/user-attachments/assets/83687b70-7673-4fd5-a220-b72ed43fc891)


### 🔹 Radar Chart
![Radar Chart](./assets/radar_chart.png)![newplot](https://github.com/user-attachments/assets/22fff4c8-4842-4ed5-9c31-04c7e8e62d4e)


## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-Learn, Streamlit)
- **Machine Learning** (Logistic Regression, StandardScaler)
- **Plotly** (Data Visualization)
- **HTML & CSS** (Custom Styling)

## 📂 Folder Structure
```
📂 Breast-Cancer-Predictor
 ├── 📂 app
 │   ├── main.py (Streamlit App)
 ├── 📂 assets
 │   ├── style.css (Custom Styles)
 ├── 📂 data
 │   ├── data.csv (Dataset)
 ├── 📂 model
 │   ├── main.py (Model Training)
 │   ├── model.pkl (Trained Model)
 │   ├── scaler.pkl (Scaler for Standardization)
 ├── README.md (Project Documentation)
 ├── requirements.txt (Dependencies)
```

## 🔧 Installation & Usage
1️⃣ **Clone the repository**
```bash
git clone https://github.com/your-username/Breast-Cancer-Predictor.git
cd Breast-Cancer-Predictor
```

2️⃣ **Create a virtual environment & install dependencies**
```bash
pip install -r requirements.txt
```

3️⃣ **Run the Streamlit app**
```bash
streamlit run app/main.py
```

## 🤖 Machine Learning Model
The prediction model is based on **Logistic Regression**, trained on the **Wisconsin Breast Cancer Dataset**:
- **Feature Scaling**: StandardScaler
- **Train-Test Split**: 80-20 ratio
- **Accuracy**: **92%** on test data

## 📬 Contact
👤 **Nidhi Saroj**  
📧 [Email](nidhisaroj964@gmail.com) | 🔗 [LinkedIn](https://www.linkedin.com/in/nidhi-saroj-705b362a6/)  

🌟 **If you found this useful, don't forget to star ⭐ the repo!**
