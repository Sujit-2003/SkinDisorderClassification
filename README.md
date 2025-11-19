 Skin Disorder Prediction (PRCP-1027-Skin-Disorder)
📌 Project Overview

This project aims to predict types of erythemato-squamous skin diseases using machine learning.
These diseases include:

Psoriasis

Seborrheic Dermatitis

Lichen Planus

Pityriasis Rosea

Chronic Dermatitis

Pityriasis Rubra Pilaris

These skin disorders are difficult to diagnose because they share many clinical and histopathological features. The model helps doctors make faster and more accurate decisions.

📊 Dataset Description

Total attributes: 34

33 numerical (linear-valued)

1 nominal feature

12 clinical features (erythema, scaling, itching, etc.)

22 histopathological features observed from skin biopsy

Each feature is rated on 0–3 severity scale

All patient identifiers were removed to maintain privacy

📁 Project Structure
.
├── skin-disorder-pred.ipynb          # Jupyter Notebook: EDA + ML Modeling
├── PRCP-1027-Skin-Disorder.docx      # Project problem statement
└── data/ (dataset files - not included)

🛠️ Dependencies

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

🚀 How to Run the Project

Place the dataset CSV files in the project folder.

Open skin-disorder-pred.ipynb in Jupyter Notebook.

Run all cells to perform:

Data loading & EDA

Feature preprocessing

Model training

Model comparison

View reports, graphs, and model evaluation results.

📌 Main Tasks Performed

Detailed Exploratory Data Analysis

Understanding correlations among clinical & histopathology features

Encoding & preprocessing

Training various ML models

Evaluating accuracy, confusion matrix, and classification metrics

Identifying the best-performing classifier

Providing insights for improving diagnosis accuracy

📝 Notes

This is a classification problem involving diseases with overlapping symptoms.

EDA and model interpretation help improve medical decision support.

The notebook contains step-by-step explanations for learning and reproducibility.

📜 License

This project is intended for academic and research purposes related to skin disorder prediction.
