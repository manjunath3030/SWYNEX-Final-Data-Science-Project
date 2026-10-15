# SWYNEX-Final-Data-Science-Project
Step 3 — README (pencil ✏️ → paste → Commit):
SWYNEX-Final-Data-Science-Project
Final Data Science Project | Data Science Internship at SWYNEX Technologies

🎯 Problem Statement
Can we predict which Titanic passengers survived based on their characteristics?

🔄 The Complete Pipeline
Phase 1: Data Preparation ✅
Fixed 177 missing Ages (median), 2 missing Embarked (mode), dropped Cabin (77% missing), removed duplicates.

Phase 2: Exploratory Data Analysis ✅
Women survived ~74% vs men ~19%
1st class ~63% vs 3rd class ~24%
Children prioritized; small families survived best; fare strongly linked to survival
Phase 3: Modeling & Evaluation ✅
Logistic Regression baseline: ~80% accuracy (80/20 split)
Evaluated with accuracy, confusion matrix, precision/recall
Model confirmed EDA insights: Sex, Pclass, Fare = top features
Phase 4: Conclusions ✅
Baseline achieves ~80%; limitations include small dataset and dropped Cabin column.

📁 Files
Final_Titanic_Project.ipynb — complete integrated notebook
titanic_cleaned.csv — cleaned dataset
💻 Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab
