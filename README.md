# 01_Student_dropout_202401100400071
📂 Project Structure
bash
Copy
Edit
├── student_dropout.csv         # Input dataset
├── dropout_prediction.ipynb   # Main Colab notebook with training and evaluation
├── README.md                   # Project documentation (this file)
🚀 Objective
To develop a classification model that predicts whether a student is at risk of dropping out using their attendance, grades, and participation levels. This enables proactive intervention by educators to support at-risk students.

📊 Dataset Features

Feature	Description
attendance	Percentage of attendance (0–100)
grades	Academic performance score (0–10)
participation	Number of participations in class
dropout_risk	Target label: yes (1) or no (0)
🧪 Technologies Used
Python 🐍

Scikit-learn (ML model training & evaluation)

Pandas & NumPy (data handling)

Seaborn & Matplotlib (visualizations)

Google Colab (Jupyter Notebook runtime)

🧠 Machine Learning Pipeline
Data Preprocessing

Encoded target labels (yes → 1, no → 0)

Standardized features using StandardScaler

Split into training (80%) and testing (20%)

Model Training

RandomForestClassifier was used for classification

Evaluation

Metrics: Accuracy, Precision, Recall, F1 Score

Visual tools: Confusion Matrix, ROC Curve, Feature Importance

📈 Results
Model achieved strong performance on the test set.

Key predictors: attendance and participation

Visualizations confirmed balanced precision and recall.

📌 How to Run
Open Google Colab

Upload the notebook dropout_prediction.ipynb

Upload student_dropout.csv when prompted

Run all cells to train the model and view results

✅ Future Enhancements
Add more features: socio-economic background, exam scores

Handle class imbalance if present

Try advanced models: XGBoost, LightGBM, or neural networks

Integrate into a web app (Flask, Streamlit)
