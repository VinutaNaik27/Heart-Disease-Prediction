# ❤️ Heart Disease Prediction

### 🩺 Machine Learning Project for Heart Disease Analysis & Prediction

> An end-to-end Machine Learning project that explores patient health data, performs data cleaning and exploratory analysis, and builds a classification model to predict the presence of heart disease.

---

## 🚀 Project Highlights

✨ **Data Cleaning & Preprocessing**
📊 **Exploratory Data Analysis (EDA)**
📈 **Data Visualization**
🤖 **Machine Learning Classification**
🎯 **Model Evaluation**
📋 **Detailed Project Report**

---

## 📌 About the Project

Heart disease is one of the major health-related challenges worldwide. Machine Learning can be used to analyze health-related data and identify patterns associated with heart disease.

This project uses the **Heart Disease UCI dataset** to explore patient information and build a machine learning pipeline for predicting heart disease.

The project follows a complete data science workflow:

```text
Dataset
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Data Preprocessing
   ↓
Machine Learning
   ↓
Model Evaluation
   ↓
Prediction
```
---
🎓 Program Context

This project was developed as part of the Job Bridge Program by Unlox.

The program provided hands-on experience with practical Data Science and Machine Learning tasks using real-world datasets.

Through this project, I gained practical experience in:

Data acquisition
Data cleaning
Exploratory Data Analysis (EDA)
Data visualization
Data preprocessing
Machine Learning
Model evaluation
Python and Jupyter Notebook
---

## 🎯 Project Objectives

The main objectives of this project are:

* 🔎 Explore and understand the heart disease dataset.
* 🧹 Identify and handle missing and inconsistent data.
* 📊 Perform exploratory data analysis.
* 📈 Visualize important patterns and relationships.
* ⚙️ Prepare the dataset for machine learning.
* 🤖 Build a classification model for heart disease prediction.
* 📏 Evaluate the model using appropriate performance metrics.

---

## 📊 Dataset

The project uses the **Heart Disease UCI dataset**.

### Dataset Information

| 📌 Property      | Details                 |
| ---------------- | ----------------------- |
| **Dataset**      | Heart Disease UCI       |
| **Records**      | 920                     |
| **Features**     | 16                      |
| **File**         | `heart_disease_uci.csv` |
| **Problem Type** | Classification          |
| **Target**       | Heart disease diagnosis |

### 🔑 Important Features

| Feature    | Description                       |
| ---------- | --------------------------------- |
| `age`      | Age of the patient                |
| `sex`      | Sex of the patient                |
| `cp`       | Chest pain type                   |
| `trestbps` | Resting blood pressure            |
| `chol`     | Cholesterol level                 |
| `fbs`      | Fasting blood sugar               |
| `restecg`  | Resting ECG results               |
| `thalch`   | Maximum heart rate achieved       |
| `exang`    | Exercise-induced angina           |
| `oldpeak`  | ST depression                     |
| `slope`    | Slope of peak exercise ST segment |
| `ca`       | Number of major vessels           |
| `thal`     | Thalassemia                       |
| `num`      | Heart disease diagnosis           |

---

## 🛠️ Technologies & Tools

### 💻 Programming Language

- Python

### 📚 Libraries

| Library | Purpose |
|---|---|
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical data visualization |
| **Scikit-learn** | Machine Learning |

### 🧰 Development Tools

| Tool | Purpose |
|---|---|
| **Jupyter Notebook** | Data analysis and model development |
| **VS Code** | Code editor and development environment |
| **Git** | Version control |
| **GitHub** | Project repository |
## 🔍 Project Workflow

### 1️⃣ Data Acquisition

The Heart Disease UCI dataset is loaded using Pandas.

```python
import pandas as pd

df = pd.read_csv("heart_disease_uci.csv")
```

---

### 2️⃣ Data Exploration

The dataset is analyzed to understand its structure and quality.

This includes:

* Dataset shape
* Column names
* Data types
* Statistical summary
* Unique values
* Missing values
* Duplicate records

---

### 3️⃣ 🧹 Data Cleaning

The dataset is checked for common data quality problems such as:

* Missing values
* Duplicate records
* Incorrect data types
* Inconsistent values
* Invalid values

The required cleaning steps are performed before building the model.

---

### 4️⃣ 📊 Exploratory Data Analysis

EDA is performed to discover patterns and relationships within the data.

The analysis includes:

* Age distribution
* Gender distribution
* Chest pain analysis
* Cholesterol distribution
* Blood pressure analysis
* Maximum heart rate analysis
* Heart disease distribution
* Feature relationships

---

### 5️⃣ 📈 Data Visualization

Visualizations are created using **Matplotlib** and **Seaborn**.

Examples include:

```text
📊 Distribution Plots
📦 Box Plots
📈 Count Plots
🔥 Correlation Analysis
📉 Feature Comparison
```

These visualizations help identify patterns and relationships between patient characteristics and heart disease.

---

### 6️⃣ ⚙️ Data Preprocessing

The data is prepared for machine learning by:

* Handling missing values
* Encoding categorical features
* Selecting relevant features
* Preparing the target variable
* Splitting the dataset into training and testing data

---

### 7️⃣ 🤖 Machine Learning

A classification model is trained using the processed dataset.

The trained model learns patterns from the available patient data and uses those patterns to make predictions about heart disease.

---

### 8️⃣ 📏 Model Evaluation

The model is evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

The complete evaluation results are available in the notebook.

---

## 📁 Project Structure

```text
❤️ Heart-Disease-Prediction/
│
├── 📊 heart_disease_uci.csv
├── 📓 heart_disease_prediction.ipynb
├── 📦 Requirements.txt
├── 📄 report3.pdf
├── 📖 README.md
└── 🚫 .gitignore
```

### 📂 File Description

| File                                | Purpose                           |
| ----------------------------------- | --------------------------------- |
| 📊 `heart_disease_uci.csv`          | Heart disease dataset             |
| 📓 `heart_disease_prediction.ipynb` | Complete analysis and ML workflow |
| 📦 `Requirements.txt`               | Required Python libraries         |
| 📄 `report3.pdf`                    | Detailed project report           |
| 📖 `README.md`                      | Project documentation             |
| 🚫 `.gitignore`                     | Files excluded from Git           |

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the Project

```bash
cd Heart-Disease-Prediction
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Environment

**Windows:**

```powershell
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r Requirements.txt
```

---

## ▶️ Run the Project

Open the project in **VS Code**.

Open:

```text
heart_disease_prediction.ipynb
```

Select your virtual environment as the **Jupyter Kernel**.

Then run the notebook cells from top to bottom.

Make sure the dataset is available in the project directory:

```text
heart_disease_uci.csv
```

---

## 📈 Project Results

The notebook provides a complete analysis of the dataset, including:

✅ Data quality checks
✅ Data cleaning
✅ Exploratory data analysis
✅ Visualizations
✅ Feature preprocessing
✅ Machine learning model training
✅ Model evaluation
✅ Prediction results

The detailed findings and project documentation are available in **`report3.pdf`**.

---

## 💡 Key Learning Outcomes

Through this project, the following concepts were practiced:

* Python for Data Science
* Pandas and NumPy
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Feature Preprocessing
* Classification
* Machine Learning
* Model Evaluation
* Jupyter Notebook

---

## 🔮 Future Improvements

Some possible improvements for this project include:

* 🔹 Comparing multiple machine learning algorithms.
* 🔹 Performing hyperparameter tuning.
* 🔹 Improving feature selection.
* 🔹 Adding cross-validation.
* 🔹 Deploying the trained model as a web application.
* 🔹 Creating an interactive dashboard for predictions.

---

## ⚠️ Disclaimer

> **This project is created for educational and academic purposes only.**
>
> The predictions generated by the model should **not be considered a medical diagnosis** or a substitute for professional medical advice.

---

## 👩‍💻 Author

### **Vinuta Naik**

🎓 Computer Science / Engineering Student
💻 Interested in **AI, Machine Learning & Data Science**

🔗 **GitHub:** [VinutaNaik27](https://github.com/VinutaNaik27)

---

## ⭐ If you found this project useful

Feel free to **star ⭐ the repository** and explore the notebook to understand the complete Machine Learning workflow.

---

### 📜 License

This project is intended for educational purposes.
