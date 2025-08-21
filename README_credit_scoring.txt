CREDIT SCORING — QUICK START (Beginner Friendly)

Files here:
- credit_synthetic.csv : Synthetic dataset you can train on immediately.
- credit_scoring_starter.ipynb : Jupyter notebook with step-by-step code.
- credit_scoring_starter.py : Python script version.
- models/ : Folder created after training to store the saved model.

Setup (Windows/Mac/Linux):
1) Install Anaconda (or Python 3.10+).
2) Create env (optional):
   conda create -n credit python=3.10 -y
   conda activate credit
3) Install packages:
   pip install pandas numpy scikit-learn matplotlib joblib

Run options:
A) Notebook:
   - Open Jupyter: jupyter notebook
   - Open credit_scoring_starter.ipynb and run the cells top-to-bottom.

B) Script:
   python credit_scoring_starter.py

Switching to a real dataset:
- Put your CSV in the same folder and change DATA_PATH at the top of the notebook/script.
- Ensure it has a binary target column named 'default' (1=default, 0=not default). If not, rename it.
- Update the list of categorical/numeric columns if needed (the code auto-detects most of it).

What to submit (typical university project):
- Notebook/script + saved model file.
- Short report (2–5 pages): data description, EDA, features, models tried, metrics (Precision, Recall, F1, ROC-AUC),
  best model & reasons, limitations, and future work.
- Slides (5–10) summarizing the same.
