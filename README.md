# ❤️ Heart Disease Predictor — Machine Learning Project

### Analyze. Predict. Understand.

Exploring machine learning for heart disease prediction.

**Heart Disease Predictor** is a machine learning project designed to estimate the likelihood of heart disease using patient health-related information. It applies supervised learning techniques to analyze clinical features and classify whether a person may have heart disease.

Built using **Python, NumPy, Pandas, and Scikit-learn**, the project demonstrates an end-to-end machine learning workflow, including dataset exploration, data preparation, model training, performance evaluation, and individual predictions.

This project is intended for educational purposes and demonstrates the practical application of machine learning in healthcare-related data analysis.

📂 **GitHub Repository:** [View Source Code](https://github.com/tapobrata2002/Heart-Disease-Predictor)

---

## 🚀 Features

- ❤️ **Heart Disease Prediction** — Predicts the presence or absence of heart disease using clinical input features.
- 📊 **Dataset Exploration** — Examines the dataset using Pandas to understand its structure and statistical properties.
- 🔍 **Data Inspection** — Checks dataset dimensions, information, descriptive statistics, and missing values.
- 🧹 **Feature & Target Separation** — Separates input features from the target variable before model training.
- ✂️ **Train-Test Split** — Divides the dataset into training and testing subsets using an 80:20 split.
- ⚖️ **Stratified Sampling** — Maintains target-class proportions during dataset splitting.
- 🧠 **Logistic Regression Model** — Uses Scikit-learn's Logistic Regression algorithm for binary classification.
- 📈 **Model Evaluation** — Evaluates model performance using accuracy scores on training and testing data.
- 🔮 **Predictive System** — Accepts individual patient feature values and generates a prediction.
- 🐍 **Python-Based Implementation** — Uses popular Python libraries for data processing and machine learning.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| NumPy | Numerical operations and input array preparation |
| Pandas | Dataset loading, inspection, and manipulation |
| Scikit-learn | Machine learning model training and evaluation |
| Logistic Regression | Binary classification algorithm |
| Jupyter Notebook | Interactive data exploration and experimentation |

---

## 📂 Project Structure

```text
Heart-Disease-Predictor/
│
├── heart disease predictor.py  # Data processing, model training,
│                               # evaluation, and prediction
│
├── heart_data.csv              # Heart disease dataset
│
├── Work Flow.png               # Project workflow visualization
│
└── README.md                   # Project documentation
```

---

## ⚙️ How It Works

### 1️⃣ Data Collection & Exploration

- The project loads the heart disease dataset using Pandas.
- The `head()` and `tail()` methods display sample records.
- Dataset dimensions and column information are inspected.
- Missing values are checked using `isnull().sum()`.
- Descriptive statistics are generated using `describe()`.
- The target variable distribution is examined using `value_counts()`.

### 2️⃣ Feature & Target Separation

- The dataset contains clinical input features and a target variable.
- The `target` column represents the classification output.
- `0` represents the absence of heart disease.
- `1` represents the presence of heart disease.
- Input features are separated into `X`, while the target is stored in `Y`.

### 3️⃣ Train-Test Split

- The dataset is divided into training and testing subsets.
- 80% of the data is allocated for training.
- 20% is reserved for testing.
- Stratified sampling maintains the target-class distribution.
- A fixed random state ensures reproducibility of the split.

### 4️⃣ Model Training

- Scikit-learn's `LogisticRegression` algorithm is used.
- The model is trained using the training dataset.
- It learns relationships between the clinical input features and the target variable.
- The trained model is then used to generate predictions.

### 5️⃣ Model Evaluation

- Predictions are generated using the training dataset.
- Training accuracy is calculated using `accuracy_score()`.
- Predictions are also generated using the testing dataset.
- Test accuracy is calculated to evaluate performance on unseen data.

### 6️⃣ Predictive System

- Individual patient information is provided as a tuple of input values.
- NumPy converts the input into an array.
- The input array is reshaped into the format required by Scikit-learn.
- The trained Logistic Regression model generates a classification.
- The output indicates whether the supplied input is classified as having heart disease.

---

## 📊 Dataset

The project uses a heart disease dataset stored in `heart_data.csv`.

The dataset contains clinical information used for binary classification.

The Python implementation separates the `target` column from the remaining input features.

**Target Classification:**

| Target Value | Meaning |
|---|---|
| 0 | No heart disease |
| 1 | Heart disease |

The dataset is loaded and explored using Pandas before being divided into training and testing subsets.

---

## 🤖 Machine Learning Model

The project uses **Logistic Regression**, a supervised machine learning algorithm commonly used for binary classification problems.

### Model Workflow

1. Load the dataset.
2. Separate input features and target labels.
3. Split the dataset into training and testing subsets.
4. Initialize the Logistic Regression classifier.
5. Train the model using training data.
6. Generate predictions on training and testing data.
7. Evaluate performance using accuracy scores.
8. Generate predictions for individual input samples.

### Evaluation Metric

The project uses classification accuracy to measure the proportion of correctly predicted observations.

\[
\text{Accuracy} =
\frac{\text{Correct Predictions}}
{\text{Total Predictions}}
\times 100
\]

The actual training and testing accuracy values are calculated when the Python script is executed.

---

## ▶️ Installation & Setup

### Prerequisites

Make sure you have the following installed:

- Python 3.9 or later
- pip (Python Package Manager)
- Git
- Visual Studio Code or Jupyter Notebook

### 1. Clone the Repository

```bash
git clone https://github.com/tapobrata2002/Heart-Disease-Predictor.git
```

### 2. Navigate to the Project Directory

```bash
cd Heart-Disease-Predictor
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

### 5. Install Required Dependencies

The repository does not currently include a `requirements.txt` file. Install the required libraries manually:

```bash
pip install numpy pandas scikit-learn
```

### 6. Run the Python Script

```bash
python "heart disease predictor.py"
```

The script will load the dataset, train the Logistic Regression model, display training and testing accuracy, and execute the sample prediction code.

---

## 🔮 Future Improvements

- Add additional classification algorithms such as Random Forest, Decision Tree, and Support Vector Machine.
- Compare multiple models using consistent evaluation metrics.
- Introduce confusion matrices and classification reports.
- Evaluate precision, recall, and F1-score.
- Improve data preprocessing and feature scaling.
- Implement cross-validation for more reliable model evaluation.
- Save the trained model using Joblib or Pickle.
- Build an interactive web interface using Flask or Streamlit.
- Add visualizations for dataset exploration and model performance.
- Improve prediction input handling through a reusable prediction function.

---

## ⚠️ Disclaimer

This project is developed for **educational and machine learning demonstration purposes only**.

Its predictions should not be interpreted as medical diagnoses or used as a substitute for professional medical advice, clinical evaluation, or treatment.

---

## 🤝 Contribution

This repository serves as a machine learning project focused on Python programming, data analysis, supervised learning, and predictive modelling.

Suggestions, feedback, and improvements are welcome.

If you find something worth improving, feel free to open an issue or submit a pull request.

---

## 👨‍💻 Author

**Tapobrata Roy**

Frontend Developer | Aspiring Full-Stack Developer

- GitHub: [tapobrata2002](https://github.com/tapobrata2002)

---

### ❤️ HEART DISEASE PREDICTOR

**Analyze. Predict. Understand.**
