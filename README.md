# 🚢 The Unsinkable: Intro to ML & Ensemble Learning

In this project, we'll be building different classification models to predict the survivability of a passenger on the titanic. The analysis can be accessed [here](analysis/the-unsinkable-intro-to-ml-ensemble-learning.ipynb).

**Author**: Po-Hsun (Ben) Chen

## Summary

In this machine learning project centered around the Titanic dataset, I systematically examined the performance of different classification models, evaluating their efficacy in predicting survival outcomes. Employing ensemble learning techniques such as random forests and boosting algorithms, the project aimed to harness the collective strengths of multiple models, resulting in a robust and accurate predictive model for survival on the Titanic.

## Data Source

The dataset used in this analysis contains 10 variables, including our target variable: `survival`. This variable takes on two values, `0` as 'No' and `1` as 'Yes'. The remaining variables consist of `pclass`, `sex`, `Age`, `sibsp`, `parch`, `ticket`, `fare`, `cabin` and `embarked`. You can access the dataset [here](https://www.kaggle.com/competitions/titanic/data?select=train.csv).

## Dependencies

All required dependencies are listed in this [conda environment file](environment.yaml).

## How to Reproduce the Analysis

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/phchen5/intro-to-ml-titanic.git
   cd intro-to-ml-titanic
   ```

2. **Download the Dataset from the Source:**
   You may need to register for a Kaggle account. After you've downloaded the dataset, place the `gender_submission.csv`, `test.csv` and `train.csv` file within a `data/` folder located in the root. You may also place it anywhere else in the repository as you like, just be sure to edit the data source path within the analysis.
3. **Set Up and Activate Environment:**

   ```bash
   conda env create -f environment.yaml
   conda activate titanic
   ```

4. **Open the Notebook:**

   ```bash
   jupyter lab analysis/the-unsinkable-intro-to-ml-ensemble-learning.ipynb
   ```

5. **Run the Cells and Have Fun Exploring!**

## Files

- `analysis/the-unsinkable-intro-to-ml-ensemble-learning.ipynb`: Jupyter notebook containing the EDA code.
- `environment.yaml`: Conda environment file listing required dependencies.
