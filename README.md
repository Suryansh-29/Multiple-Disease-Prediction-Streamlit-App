# Health Assistant - Multiple Disease Prediction System

## 🏥 About the Project
Health Assistant is a web-based application that helps users predict the likelihood of three major diseases:
- **Diabetes**
- **Heart Disease**
- **Parkinson's Disease**

The system utilizes pre-trained machine learning models to provide predictions based on user inputs. It is built using **Streamlit**, making it easy to use and accessible.

## 🚀 Features
- User-friendly interface built with **Streamlit**
- Predicts **Diabetes**, **Heart Disease**, and **Parkinson's Disease**
- Machine learning models loaded using **pickle**
- Provides instant results based on user input
- Modular design with a sidebar navigation menu

## 🛠️ Tech Stack
- **Python**
- **Streamlit**
- **Scikit-Learn**
- **Pickle**
- **Streamlit Option Menu**

## 📂 Project Structure
```
📁 Multiple-Disease-Prediction
│── saved_models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── parkinsons_model.sav
│── main.py
│── requirements.txt
│── README.md
```

## 🔧 Installation & Setup
Follow these steps to set up and run the project locally:

### 1️⃣ Clone the repository:
```sh
git clone https://github.com/your-username/health-assistant.git
cd health-assistant
```

### 2️⃣ Install dependencies:
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the application:
```sh
streamlit run main.py
```

## 📜 Usage
1. Open the application in your browser after running the command above.
2. Choose a prediction type from the sidebar: **Diabetes**, **Heart Disease**, or **Parkinson's Disease**.
3. Enter the required medical details.
4. Click the **Prediction Button** to see the results.

## 📦 Dependencies
- **streamlit**
- **pickle**
- **numpy**
- **scikit-learn**
- **streamlit-option-menu**

To install all dependencies, use:
```sh
pip install -r requirements.txt
```

## 🧑‍💻 Model Information
- **Diabetes Model**: Predicts whether a person has diabetes based on factors like glucose level, BMI, and insulin.
- **Heart Disease Model**: Analyzes multiple health parameters to assess the likelihood of heart disease.
- **Parkinson's Model**: Uses voice-related parameters to predict Parkinson's disease.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

---
**🚀 Stay Healthy, Stay Safe!**

