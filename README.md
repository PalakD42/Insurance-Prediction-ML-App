# 🏥 Health Insurance Purchase Prediction

An interactive Machine Learning web application built using **Python, Scikit-learn, and Streamlit**. This project uses Logistic Regression to predict whether a customer is likely to purchase health insurance based on their details.

🌐 **[Try the Live Application](https://insurance-prediction-ml-app-xreaampoc79bxjtcpnienk.streamlit.app/)**

## 📖 Overview

This project demonstrates how Machine Learning can be used to analyze customer information and predict insurance purchase behavior.

The application loads an insurance dataset, preprocesses the data, trains a Logistic Regression model, and provides an interactive interface where users can enter customer details to receive a prediction.

The model classifies the result into two categories:

- ✅ Customer is predicted to buy insurance.
- ❌ Customer is predicted not to buy insurance.

## ✨ Features

- 📊 Insurance dataset loading and preprocessing
- 🔍 Exploratory data analysis
- 🤖 Logistic Regression model
- 📈 Training and testing data split
- 🖥️ Interactive Streamlit web interface
- 🎛️ Dynamic customer input controls
- ⚡ Instant prediction through the application
- ☁️ Live deployment using Streamlit Community Cloud

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data loading and manipulation |
| NumPy | Numerical operations |
| Scikit-learn | Machine Learning model |
| Logistic Regression | Classification algorithm |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Streamlit | Interactive web application |

## 📂 Project Structure

```text
Insurance-Prediction-ML-App/
│
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/PalakD42/Insurance-Prediction-ML-App.git
```

### 2. Navigate to the project directory

```bash
cd Insurance-Prediction-ML-App
```

### 3. Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate it:

**Windows:**
```bash
venv\Scripts\activate
```

**Linux/macOS:**
```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

Start the Streamlit application using:

```bash
streamlit run app.py
```

The application will open in your browser. If it does not open automatically, visit:

```text
http://localhost:8501
```

## ⚙️ How It Works

1. Load the insurance dataset using Pandas.
2. Remove the unnecessary customer ID column.
3. Convert categorical Yes/No values into numerical values.
4. Separate the input features and target variable.
5. Split the dataset into training and testing sets.
6. Train a Logistic Regression classification model.
7. Collect customer details through Streamlit sidebar inputs.
8. Pass the entered details to the trained model.
9. Display the predicted insurance purchase result.

## 🧠 Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is a supervised machine learning classification algorithm used to predict categorical outcomes.

In this project, it predicts whether a customer is likely to purchase insurance based on the available customer information.

The target variable is:

- `0` – Customer will not buy insurance.
- `1` – Customer will buy insurance.

## 🌐 Live Demo

<text color="success" weight="semibold">Application deployed successfully</text>

Try the application here:

👉 **[Health Insurance Prediction App](https://insurance-prediction-ml-app-xreaampoc79bxjtcpnienk.streamlit.app/)**

## 🚀 Future Improvements

- Improve model performance through hyperparameter tuning.
- Compare Logistic Regression with other classification algorithms.
- Add model evaluation metrics and visualizations.
- Improve the user interface and application design.
- Add more customer insights and prediction explanations.
- Integrate a database for storing prediction history.

## 🎯 Learning Outcomes

Through this project, I explored:

- Data preprocessing using Pandas.
- Handling categorical variables.
- Supervised Machine Learning.
- Logistic Regression classification.
- Training and testing dataset splitting.
- Building interactive applications using Streamlit.
- Deploying Machine Learning applications online.

## 👩‍💻 Author

**Palak Dwivedi**

- GitHub: [PalakD42](https://github.com/PalakD42)
- LinkedIn: [Palak Dwivedi](https://www.linkedin.com/in/palak-dwivedi-019445360/)
- Portfolio: [My Portfolio](https://palakd42.github.io/MyPortfolio/)

---

⭐ If you find this project interesting, consider giving the repository a star!

*This project is developed for educational and learning purposes. Predictions are model outputs and should not be treated as actual insurance purchase decisions.*
