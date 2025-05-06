
# EA Sports FC 24 – Player Rating Prediction

**EA Sports FC 24** is a machine learning project that predicts future ratings of male football players in the FIFA video game series, focusing on the next three years based on historical player data. The goal is to build predictive models using machine learning algorithms to forecast player ratings, which are essential for game balancing and improving player experience.

---

## 🌐 Project Overview

This project aims to predict the ratings of male players in FIFA 24 for the next three years. It involves data preprocessing, feature engineering, model training, and evaluation of multiple machine learning algorithms.

- **Data Preprocessing**: Cleaning and transforming raw player data into a structured format.
- **Modeling**: Using machine learning models like Random Forest, Gradient Boosting, Voting Regressor to predict future player ratings.
- **Evaluation**: Assessing model performance using metrics like RMSE and R².
- **Final Prediction**: Generating future player ratings and integrating them into a final dataset.

---

## 🛠️ Technologies & Tools

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Notebook**: Jupyter Notebook
- **Dataset**: [EA Sports FC 24 Complete Player Dataset (Kaggle)](https://www.kaggle.com/datasets/stefanoleone992/ea-sports-fc-24-complete-player-dataset)
- **Machine Learning Models**: Random Forest, Gradient Boosting, Voting Regressor
- **Evaluation Metrics**: RMSE, R²

---

## 📁 Repository Structure

```
EA_Sports_FC24/
├── prog/                     → Source code and notebook 
│   └── FifaFDSML.ipynb        → Complete Jupyter notebook for the project. 
│
├── docs/                     → Documentation
│   └── Project_Report_EA_Sports_FC24.pdf  → Project report 
│
├── README.md                 → Project documentation
└── .gitignore             → Git ignore file to exclude large files like CSVs
```

---

## 🚀 How to Use

1. Clone the repository: 
   ```bash
   git clone https://github.com/Marco210210/EA-Sports-FC24.git
   ```

2. Open the Jupyter notebook `FifaFDSML.ipynb` to see the full workflow.

3. The dataset files are not included in the repository due to size limitations. Please download the dataset from Kaggle using the following link: [EA Sports FC 24 Complete Player Dataset](https://www.kaggle.com/datasets/stefanoleone992/ea-sports-fc-24-complete-player-dataset)

4. The notebook will automatically handle the data preprocessing and create the required datasets.

5. Refer to `Project_Report_EA_Sports_FC24.pdf` in the `docs/` directory for a detailed explanation of the project methodology, results, and conclusions.

---

## 📄 Documentation

- [Project Report (PDF)](docs/Project_Report_EA_Sports_FC24.pdf)

---

## 👥 Contributors

- [Arcangeli Giovanni](https://github.com/GiovanniArcangeli)
- Di Maio Marco

---

## 📄 License

This project is licensed under the [CC BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  

You may share and adapt this work for non-commercial purposes only, **as long as you give appropriate credit** and **distribute your contributions under the same license**.  
For commercial use, **explicit permission from the authors is required**.
