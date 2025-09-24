# PyTorch League of Legends Match Prediction 🕹️

This project is my **final submission for the Deep Learning with PyTorch course**.  
It uses match statistics (kills, deaths, assists, gold earned, etc.) to **predict the outcome of a League of Legends match** (Win/Loss) using a Logistic Regression model implemented in PyTorch.

---

## 📌 Project Overview
- Implemented a **Logistic Regression model** from scratch using PyTorch.
- Applied **data preprocessing** (scaling, train-validation-test split).
- Trained the model using **Binary Cross Entropy with Logits Loss** and the **Adam optimizer**.
- Performed **hyperparameter tuning** with a simple grid search on learning rates.
- Evaluated the model with multiple metrics:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - ROC AUC  

---

## 🛠️ Tech Stack
- **Python 3.10+**
- **PyTorch**
- **scikit-learn**
- **pandas, numpy, matplotlib**

---
## 📂 Project Structure
<pre>

DL with PyTorch Final Project
├── venv/
├── league_of_legends_data_large.csv                                  # Dataset (not included, add your own CSV)
├── Final_Project_League_of_Legends_Match_Predictor_v2_completed      # Jupyter notebooks
├── requirements.txt                                                  # Dependencies
├── README.md                                                         # Project description
└── .gitignore                                                        # Ignore unnecessary files

</pre>
---
 
## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/pytorch-lol-match-prediction.git
   cd pytorch-lol-match-prediction
   ```
2. Create a virtual environment & install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate   # (Linux/Mac)
   venv\Scripts\activate      # (Windows)
   pip install -r requirements.txt
   ```
3. Download the Dataset:
   
4. Run the notebook / script:
   ```bash
   jupyter notebook Final_Project.ipynb
   ```

---

## 📊 Results

Final Model Performance (after tuning):

- Accuracy: 50%
- Precision: 51%
- Recall: 49%
- F1-score: 50%
- ROC AUC: 0.505

⚠️ Note: Performance is close to random guess (50%).
This shows the dataset is very challenging and may need feature engineering, deeper models, or additional domain-specific insights.

---

✨ Future Improvements

- Add neural network layers (MLP instead of plain logistic regression).
- Try dropout & batch normalization to reduce overfitting.
- Use advanced optimizers / schedulers.
- Perform feature selection / engineering from raw match stats.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit PRs.

---

## 🎓 Certificate
[Introduction to Neural Network and PyTorch](https://www.coursera.org/account/accomplishments/certificate/AOJ1ARS7O1VV)

---

📜 License

This project is for educational purposes.
You are free to use/modify under the [MIT License]()
   
