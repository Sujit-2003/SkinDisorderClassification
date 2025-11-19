# SkinDisorderClassification
Project Overview
This project focuses on predicting various classes of skin diseases using machine learning techniques. The aim is to assist doctors in early identification of erythemato-squamous diseases, such as psoriasis, seborrheic dermatitis, lichen planus, pityriasis rosea, chronic dermatitis, and pityriasis rubra pilaris. These diseases share many clinical and histopathological features, making diagnosis challenging.

Dataset Description
The dataset contains 34 attributes: 33 linear-valued features and 1 nominal feature.

Clinical evaluation consists of 12 features; histopathological evaluation consists of 22 features assessed from skin samples under a microscope.

Features record severity on a scale from 0 (not present) to 3 (maximum presence).

Important attributes include erythema, scaling, itching, koebner phenomenon, family history, age, and various histopathological markers.

Patient identifiers were removed to protect privacy.​

Project Structure
skin-disoder-pred.ipynb: Full Jupyter notebook containing data analysis, feature engineering, machine learning model creation, evaluation, and comparisons.

PRCP-1027-Skin-Disorder.docx: Project problem statement and dataset description.

Dataset file(s) (external, usually provided as CSVs during model training).
Install dependencies with:
pip install pandas numpy matplotlib seaborn scikit-learn
Usage Instructions
Place the dataset files in the working directory.

Open the skin-disoder-pred.ipynb notebook in Jupyter or any compatible environment.

Run the notebook sequentially to perform:

Data loading and exploratory analysis.

Feature engineering and preprocessing.

Training and evaluation of multiple classification models.

Review model performance reports and diagnostic visualizations for insights.

Main Tasks
Conduct exploratory data analysis to understand clinical and histopathological features.

Build predictive models to classify skin diseases based on attributes.

Compare multiple machine learning models to identify the best performer.

Develop recommendations to aid quicker and more accurate diagnosis by doctors.
Notes
Classification task involves diseases with overlapping symptoms and biopsy challenges.

The notebook contains detailed comments for reproducibility and educational purposes.

For further information, consult the attached project documentation.

License
This project is intended for academic and research purposes related to skin disorder prediction.
