
# 🎓 Student Performance Prediction | Machine Learning

An End-to-End Machine Learning project that predicts students' mathematics performance based on demographic information, parental education, lunch type, test preparation, and reading and writing scores.

The project uses Python and Machine Learning algorithms to analyze student data, train predictive models, and provide predictions through a Flask-based web application.

## 🚀 Project Overview

The main objective of this project is to predict students' mathematics scores using various academic and demographic factors.

The application takes student information as input and uses a trained Machine Learning model to estimate the student's mathematics performance.

This project demonstrates an end-to-end Machine Learning workflow, starting from data preprocessing and exploratory data analysis to model training, evaluation, and web application deployment.

## ✨ Key Features

- **Data Preprocessing:** Cleaning and preparing raw student datasets.
- **Exploratory Data Analysis (EDA):** Understanding relationships between student attributes and academic performance.
- **Feature Engineering:** Preparing relevant features for model training.
- **Model Training:** Training and evaluating multiple Machine Learning algorithms.
- **Model Selection:** Selecting a suitable predictive model based on evaluation metrics.
- **Prediction Pipeline:** Automating preprocessing and prediction.
- **Flask Web Application:** Providing a user-friendly interface for entering student information and generating predictions.
- **Model Serialization:** Saving trained models and preprocessing objects for reuse.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Scikit-learn | Machine Learning and preprocessing |
| CatBoost | Gradient boosting algorithm |
| Matplotlib | Data visualization |
| Seaborn | Exploratory data analysis |
| Flask | Web application development |
| Dill | Model and object serialization |
| HTML/CSS | Frontend interface |

## 🧠 Machine Learning Workflow

The project follows an end-to-end Machine Learning pipeline:

1. **Data Collection:** Loading the student performance dataset.
2. **Data Preprocessing:** Handling missing values and preparing categorical and numerical features.
3. **Exploratory Data Analysis:** Analyzing patterns and relationships in the dataset.
4. **Feature Engineering:** Transforming input features into a suitable format.
5. **Model Training:** Training different regression algorithms.
6. **Model Evaluation:** Comparing model performance using evaluation metrics.
7. **Model Selection:** Selecting the best-performing model.
8. **Prediction Pipeline:** Using the trained model to generate predictions.
9. **Deployment:** Integrating the prediction pipeline with a Flask web application.

## 📊 Input Features

The model uses the following student information:

| Feature | Description |
|---|---|
| Gender | Student's gender |
| Race/Ethnicity | Student's race or ethnicity group |
| Parental Level of Education | Parent's education qualification |
| Lunch | Standard or free/reduced lunch |
| Test Preparation Course | Whether the student completed test preparation |
| Reading Score | Student's reading examination score |
| Writing Score | Student's writing examination score |

**Target Variable:** Mathematics Score

## 📂 Project Structure

```text
mlproject/
│
├── .ebextensions/
├── .github/
│   └── workflows/
│
├── artifacts/
│   ├── model.pkl
│   ├── preprocessor.pkl
│   └── other generated artifacts
│
├── catboost_info/
│
├── notebook/
│   └── Data analysis and model training notebooks
│
├── src/
│   ├── components/
│   ├── pipeline/
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── application.py
├── requirements.txt
├── setup.py
└── README.md
```

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Rishabhmishra-tech/mlproject.git
```

### 2. Navigate to the Project Directory

```bash
cd mlproject
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 4. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 5. Install the Project Package

```bash
pip install -e .
```

### 6. Run the Application

```bash
python application.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

Enter the required student information to generate a mathematics score prediction.

## 📈 Model Evaluation

The project uses regression algorithms to predict student mathematics scores.

Model evaluation can be performed using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help evaluate prediction errors and the model's ability to explain variations in student performance.

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- End-to-end Machine Learning project development.
- Data cleaning and preprocessing.
- Exploratory Data Analysis using Pandas and visualization libraries.
- Feature engineering and model training.
- Regression algorithms and model evaluation.
- Building reusable Machine Learning pipelines.
- Model serialization using Dill.
- Integrating Machine Learning models with Flask.
- Deploying Machine Learning applications.

## 🔮 Future Improvements

- Improve model performance through hyperparameter tuning.
- Add interactive data visualizations.
- Integrate additional student performance indicators.
- Improve the user interface.
- Deploy the application on a cloud platform.
- Add prediction history and performance analytics.

## 👨‍💻 Author

**Rishabh Kumar Mishra**

- GitHub: [Rishabhmishra-tech](https://github.com/Rishabhmishra-tech)
- LinkedIn: [Connect with me](https://linkedin.com/in/rishabhmishra-b693781ba)

---
