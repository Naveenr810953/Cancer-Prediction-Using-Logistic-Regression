 # 🔬 Breast Cancer Prediction Tool

A machine learning-powered web application that predicts whether a breast tumor is **Malignant** (cancerous) or **Benign** (non-cancerous) using real medical data. Built with **Python**, **Streamlit**, and **Scikit-learn**.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-00BFFF?style=for-the-badge&logo=mlflow&logoColor=white)
 

---

## 📊 Features

- **Breast Cancer Detection** – Predict whether a tumor is cancerous based on medical features
- **Interactive Sliders** – Input real-valued features from medical reports
- **Confidence Score** – Displays probability of prediction
- **Clean UI** – Built using Streamlit with a responsive layout
- **Real Dataset** – Uses the trusted Wisconsin Breast Cancer dataset

---

## 🎯 How It Works

The predictor uses a **Logistic Regression** model trained on the **Wisconsin Breast Cancer Dataset** to classify tumor data:

1. **Model Training**:
   - Dataset: `sklearn.datasets.load_breast_cancer()`
   - Split: 80% training, 20% testing
   - Model: Logistic Regression with high iteration limit for convergence

2. **User Input**:
   - 30 tumor-related features (e.g., mean radius, texture, concavity, etc.)
   - Sliders in sidebar dynamically adjust feature values

3. **Prediction Output**:
   - Returns:
     - 🟥 **Malignant (Cancerous)**
     - ✅ **Benign (Not Cancerous)**
   - Also shows **confidence probability**

---

## 🚀 Usage

### Clone the repository:
```bash
git clone https://github.com/your-username/cancer-prediction-tool.git
cd cancer-prediction-tool
```

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Run the Streamlit app:
```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
cancer-prediction-tool/
├── app.py                # Main Streamlit app
├── requirements.txt      # Required Python packages
└── README.md             # Project documentation
```

---

## 🌐 UI Overview

| Component       | Description                                  |
|----------------|----------------------------------------------|
| Sidebar         | Feature sliders for 30 tumor-related values |
| Main Panel      | Prediction result and probability score     |
| Alert Section   | Malignant / Benign output with icons        |
| Disclaimer      | Medical disclaimer shown at bottom          |

---

## 📊 Model Details

- **Algorithm**: Logistic Regression
- **Training Split**: 80/20
- **Features Used**: All 30 features from dataset
- **Max Iterations**: 10,000 (for convergence)
- **Libraries**:
  - `scikit-learn`
  - `numpy`
  - `streamlit`

---

## 🔧 Technologies Used

- **Python** – Main programming language
- **Streamlit** – UI for ML app
- **Scikit-learn** – ML model and dataset
- **NumPy** – Numerical array operations

---

## 📝 TODO

- ✅ Cache model training to speed up app
- 📈 Add feature importance visualization (e.g., SHAP)
- 🔄 Add support for alternative ML models (e.g., SVM, RF)
- 📥 Enable download of prediction reports
- 🌐 Deploy via Streamlit Cloud or Hugging Face Spaces

---

## ⚠️ Disclaimer

> ⚠️ **This tool is for educational purposes only.**  
> It is **not a medical device** and should **not be used for real diagnoses**.  
> Always consult certified medical professionals for accurate health assessments.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a Pull Request

---

## 👨‍💻 Developer

**Naveen Kumar S**  
📧 Email: navee4147@gmail.com  
💻 GitHub: [Naveenr810953](https://github.com/Naveenr810953)

---

## ⭐️ Show Your Support

If you found this project helpful, please give it a ⭐️ on GitHub!

---
