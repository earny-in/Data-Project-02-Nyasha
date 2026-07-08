# 🤖 AI Placement Salary Predictor

An AI-powered Machine Learning project that predicts a student's expected placement salary package based on academic performance, technical skills, internships, certifications, and placement-related attributes.

---

## 📖 About the Project

The **AI Placement Salary Predictor** is a Machine Learning project designed to estimate the salary package a student is likely to receive during campus placements.

The model is trained on historical placement data containing student academic records, technical skills, aptitude scores, coding performance, internships, projects, certifications, communication skills, and other placement-related features.

After training, the model can predict the expected salary package of a new student by analyzing their profile.

This project demonstrates the complete Machine Learning workflow, from data preprocessing to model deployment-ready prediction.

---

# 🎯 Project Objectives

- Predict student placement salary packages.
- Understand factors affecting placement salaries.
- Learn the complete Machine Learning pipeline.
- Perform data preprocessing and visualization.
- Train and evaluate regression models.
- Generate predictions for new student profiles.

---

# 💡 Problem Statement

Campus placements depend on several factors such as academic performance, coding skills, internships, projects, certifications, and communication skills.

Manually estimating a student's expected salary package is difficult because many attributes contribute to placement outcomes.

This project uses Machine Learning to learn these relationships and predict salary packages accurately based on historical placement data.

---

# 🧠 Machine Learning Approach

### Learning Type

**Supervised Learning**

### Problem Type

**Regression**

The model learns from historical student placement records where both the student information and salary package are available.

After training, the model predicts the salary package for unseen student profiles.

---

# 📊 Dataset Information

**Dataset Name**

AI Placement Predictor Dataset

**Source**

Kaggle

**Dataset Type**

CSV

**Machine Learning Task**

Regression

---

## 📋 Dataset Features

The dataset contains student-related information including:

| Feature | Description |
|----------|-------------|
| Student ID | Unique student identifier |
| Age | Student age |
| Gender | Male/Female |
| Branch | Engineering branch |
| College Tier | Tier of college |
| CGPA | Academic performance |
| Attendance Percentage | Overall attendance |
| Coding Skill Score | Programming skills |
| DSA Score | Data Structures & Algorithms score |
| Aptitude Score | Aptitude performance |
| Logical Reasoning Score | Reasoning ability |
| Communication Skill Score | Communication rating |
| Projects Count | Number of completed projects |
| Certifications Count | Number of certifications |
| GitHub Repositories | GitHub project count |
| Internship Count | Number of internships |
| Leadership Score | Leadership activities |
| Extracurricular Score | Extra-curricular performance |
| Mock Interview Score | Interview performance |
| Placement Status | Placed / Not Placed |
| Salary Package (LPA) | Target Variable |

---

# 🎯 Target Variable

**Salary Package (LPA)**

The model predicts the expected placement salary package of a student.

---

# ⚙️ Project Workflow

```text
Collect Dataset
        │
        ▼
Data Preprocessing
        │
        ▼
Handle Missing Values
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Train-Test Split
        │
        ▼
Train ML Model
        │
        ▼
Evaluate Model
        │
        ▼
Predict Salary
```

---

# 🔄 How the Project Works

### Step 1

Load the placement dataset.

### Step 2

Clean the dataset by handling missing values and removing unnecessary information.

### Step 3

Perform Exploratory Data Analysis (EDA) to understand relationships between different features.

### Step 4

Convert categorical values into numerical form if required.

### Step 5

Split the dataset into Training and Testing sets.

### Step 6

Train a Machine Learning Regression model.

### Step 7

Evaluate model performance using suitable evaluation metrics.

### Step 8

Accept a new student's profile as input.

### Step 9

Predict the expected placement salary package.

---

# 📁 Repository Structure

```text
AI-Placement-Salary-Predictor/
│
├── Learning/
│   ├── pandas.md
│   ├── numpy.md
│   ├── ML-Learning/
│   │   ├── Supervised-Learning.md
│   │   ├── Unsupervised-Learning.md
│   │   └── Notes.md
│
├── Implementation/
│   ├── data/
│   │   ├── ai_placement_predictor.csv
│   │   └── README.md
│   │
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── model_testing.py
│   ├── prediction.py
│   ├── requirements.txt
│   │
│   ├── output/
│   │   ├── model.pkl
│   │   ├── graphs/
│   │   └── results.csv
│
├── Images/
│   ├── output.png
│   ├── accuracy.png
│   ├── prediction.png
│   └── feature_importance.png
│
├── Report/
│   └── Project_Report.pdf
│
├── .gitignore
│
└── README.md
```

---

# 📈 Sample Prediction

### Input

```
CGPA : 8.9

Coding Score : 92

DSA Score : 90

Projects : 5

Internships : 2

Communication : 88

Certifications : 6
```

### Predicted Output

```
Expected Salary Package

₹14.8 LPA
```

---

# 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Pickle

---

# 📚 Python Libraries

- pandas
- numpy
- matplotlib
- sklearn
- pickle

---

# 📊 Machine Learning Algorithms (To Compare)

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

The model with the best performance will be selected for prediction.

---

# 📈 Model Evaluation

The trained model will be evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 🚀 Future Improvements

- Web-based prediction interface using Flask.
- Real-time student profile prediction.
- Upload student details through CSV.
- Salary prediction visualization dashboard.
- Model deployment on the cloud.
- Support for multiple placement datasets.

---

# 🎓 Learning Outcomes

By completing this project, you will understand:

- Data Collection
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis
- Supervised Learning
- Regression
- Model Training
- Model Testing
- Model Evaluation
- Prediction Systems

---

# 👨‍💻 Author

**Nyasha Gupta**

Computer Science Engineering Student

Currently learning:

- Artificial Intelligence
- Machine Learning
- Data Science
- Python
- Java

---

# ⭐ Acknowledgement

Dataset obtained from Kaggle for educational and learning purposes.

This project is developed as part of an AI & Machine Learning Internship to understand the end-to-end Machine Learning workflow for salary prediction.
