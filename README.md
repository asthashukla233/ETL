🚢 Titanic Feature Selection & Preprocessing
This project demonstrates a complete data preprocessing and feature selection pipeline using the Titanic dataset. It showcases how to clean data, apply transformations, and select the most relevant features using SelectKBest.

📌 Features
Data Cleaning (Handling missing values)

Feature Engineering

Pipeline-based preprocessing with:

StandardScaler for numerical features

OneHotEncoder for categorical features

Feature Selection using ANOVA F-test (f_classif)

🛠️ Requirements
Python 3.x

pandas

numpy

seaborn

scikit-learn

Install requirements:

bash
Copy
Edit
pip install pandas numpy seaborn scikit-learn
🚀 Usage
Clone the repo

Open the notebook:

bash
Copy
Edit
jupyter notebook "task_1 (2).ipynb"
Run all cells to see preprocessing and feature selection in action.

📈 Dataset
The notebook uses the Titanic dataset provided by Seaborn:

python
Copy
Edit
df = sns.load_dataset('titanic')
📊 Output Example
After running the pipeline, the selected features and transformed datasets are displayed using Pandas DataFrames.
