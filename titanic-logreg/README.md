### Goal
The goal of this notebook is to predict which passengers of the Titanic have survived and which have not. The pipeline is end-to-end; we clean the data, one-hot encode categorical data, normalize using z-scores, implement our own version of gradient descent and logistic regression and compare the results to sklearn.LogisticRegression. 

### Results
Training set accuracy: 0.8070739549839229
Testing set accuracy: 0.7790262172284644
F1: 0.7035175879396985
ROC-AUC: 0.8327669049572248

Confusion Matrix: 
- True positives: 70
- False positives: 23
- True negatives: 36
- False negatives: 138

### Data
You can download titanic.csv from Kaggle: https://www.kaggle.com/datasets/yasserh/titanic-dataset.
Please make sure you (re-)name it as `titanic.csv'. 

### Reproduce
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook


