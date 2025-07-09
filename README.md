# adakole_machine_learning_project
University Admission Prediction – Python Project  
University Admission Prediction
🚀 Project Overview
This project explores the use of machine learning to predict university admission outcomes based on a student's academic and extracurricular profile. The goal is to demystify the admissions process by identifying key factors that influence decisions and providing a data-driven tool to estimate a student's chances of being accepted, rejected, or waitlisted.

This was developed as an academic project to apply data analysis, feature engineering, and classification modeling techniques to a real-world problem.

✨ Key Features
Admission Status Prediction: Classifies student profiles into one of three categories: Accepted, Rejected, or Waitlisted.

Feature Engineering: Creates insightful new features from raw data, such as an Academic_Score and GPA_Category, to improve model performance.

Comparative Model Analysis: Implements and evaluates three different classification algorithms to determine the most effective approach:

Logistic Regression

Linear Discriminant Analysis (LDA)

K-Nearest Neighbors (KNN)

Performance Evaluation: Uses a comprehensive set of metrics (Accuracy, Precision, Recall, F1-Score) and confusion matrices to rigorously assess and compare model performance.

🛠️ Technology Stack
Language: Python

Libraries:

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Scikit-learn: For implementing machine learning models and evaluation metrics.

Matplotlib & Seaborn: For data visualization and plotting results.

Environment: Jupyter Notebook

🔬 Methodology
Data Sourcing & Cleaning: The project utilizes the "Student Admission Dataset" from Kaggle, containing 75 student records with features like GPA, SAT Score, and number of extracurricular activities.

Feature Engineering: To enhance the predictive power of the models, several new features were created:

GPA Category: Grouped GPAs into Low, Medium, and High.

Activity Level: Categorized the number of extracurriculars.

Academic Score: A composite score calculated from GPA and SAT scores.

SAT Percentile: The percentile rank of a student's SAT score.

Modeling: Three distinct classification models were trained on the engineered dataset to predict the Admission_Status.

Evaluation: The models were evaluated on a test set. The primary metrics used for comparison were accuracy, precision, recall, and F1-score, with a focus on weighted averages to account for class distribution.

##📊 Results

The models performed with high accuracy, demonstrating the effectiveness of the feature engineering and modeling approach.

Linear Discriminant Analysis (LDA): Emerged as the top-performing model with an accuracy of 98.7%. It showed excellent capability in distinguishing between all three admission classes.

Logistic Regression: A close second, achieving 97.3% accuracy.

K-Nearest Neighbors (KNN): Performed well with 96% accuracy but showed slightly more difficulty in correctly classifying Waitlisted students.

🚧 Limitations and Future Work
Dataset Size: The primary limitation is the small dataset of only 75 records, which may limit the generalizability of the models.

Class Imbalance: The Waitlisted category had fewer samples, making it a more challenging class for the models to learn.

Future enhancements could include:

Expanding the dataset with more student records.

Applying techniques to address class imbalance.

Experimenting with more advanced models like Decision Trees, SVM, or ensemble methods (e.g., Random Forest).
