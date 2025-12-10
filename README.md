# student-performance-prediction.
Author: Yvonne Zhang
  Final Project

This project evaluates whether demographic and socio-economic background variables can be used to predict student academic success. Logistic Regression and Random Forest models are implemented and compared.

To avoid data leakage, all grade-related variables (math, reading, writing scores, and any derived averages) were removed prior to training the models.

Repository Contents
YvonneZhang-Predicting_Student_Academic_Success.ipynb   # Full notebook analysis
yvonnezhang+predicting_student_academic_success.py      # Script version
StudentsPerformance.csv                                 # Raw dataset (Kaggle)
README.md                                               # Documentation

Dataset Source

This project uses the Students Performance in Exams dataset from Kaggle:
https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

The dataset includes demographic, socio-economic, parental education, lunch type, test preparation course, and grade variables.
All grade variables were excluded from modeling.

Models Implemented
## Models Implemented

### 1. Logistic Regression
- Baseline model  
- Easy to interpret  

### 2. Random Forest
- Tuned using hyperparameters  
- Handles non-linear relationships  
- Provides feature importance  


Reproduction Instructions (Required by Instructor)
Install necessary packages

If running locally:
### Install packages
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Run the script
```bash
python yvonnezhang+predicting_student_academic_success.py
```

### Or open the notebook
```bash
YvonneZhang-Predicting_Student_Academic_Success.ipynb
```



Notes

The project was intentionally designed to eliminate data leakage before training.

The notebook contains the full workflow: data cleaning, feature engineering, model training, evaluation, and visualization.
