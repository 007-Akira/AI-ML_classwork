# AI & ML Classwork — Lab Index

An index of the exercises and algorithms in [AI_LAB_1ipynb.ipynb](AI_LAB_1ipynb.ipynb). Section links open the corresponding heading in the original Colab notebook. Cell numbers below are **1-based positions**, including markdown cells, in the local notebook.

## Day / date record

The notebook does not contain class dates or execution timestamps, so dates are marked **Not recorded** below. Notebook order is used for navigation; it does not establish which topics were completed on the same day. The existing Git commit records the preprocessing script and CSV on **23 July 2026**, but that is a commit date rather than a confirmed class date.

## Section and algorithm index

| Class date | Section / algorithm | Notebook cells | Work covered |
| --- | --- | --- | --- |
| Not recorded | [Data preprocessing](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=7VdH_k3WID_s) | 1–42 | News articles: inspection, missing values, duplicates, IQR outliers, encoding, scaling, correlation, feature engineering, text cleaning, train/test split, SMOTE, and CSV export. |
| Not recorded | [Simple linear regression](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=sb0SnrRQII71) | 43–50 | Predict salary from experience; fit a regression line and evaluate MAE, MSE, RMSE, and R². |
| Not recorded | [Multiple linear regression](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=k3Icb5F22RLd) | 51–52 | Predict salary using experience, education level, weekly hours, and project count; inspect coefficients and regression metrics. |
| Not recorded | [Dijkstra’s algorithm](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=mS9gi-DzIAlm) | 53–55 | Find distances from a starting node in a weighted graph using a priority queue. |
| Not recorded | [A* search](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=Pitlu1hMUqC-) | 56–58 | Search a weighted graph using accumulated cost and a heuristic; return the goal cost. |
| Not recorded | [Breadth-first search (BFS)](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=7O78zfPXHBDF) | 60–61 | Traverse a graph level by level with a queue. |
| Not recorded | [Depth-first search (DFS)](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=U0yHeSDBHbzF) | 62–63 | Traverse a graph recursively with a visited set. |
| Not recorded | [Greedy best-first search](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=xY-QtQ_7Hv71) | 64–65 | Choose the next graph node using its heuristic value. |
| Not recorded | [Classification data preparation](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=dUMpIsOGp7-B) | 66–74 | Load the Breast Cancer Wisconsin dataset; inspect missing values, remove duplicates, plot classes/features, and make a stratified 80/20 split. |
| Not recorded | [Decision tree](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=HtiIwV9RrLvv) | 75–84 | Train DecisionTreeClassifier; evaluate accuracy, classification report, and confusion matrix; inspect feature importance, plot the tree, and compare train/test accuracy. |
| Not recorded | [Random forest](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=KRUuqHOMupzj) | 85–90 | Train a 100-tree RandomForestClassifier; evaluate accuracy, classification report, and confusion matrix. |
| Not recorded | [Support vector machine (SVM)](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=bKLA_-JexFo1) | 91–98 | Standardize features and train an RBF-kernel SVC; evaluate accuracy, classification report, and confusion matrix. |
| Not recorded | [Logistic regression](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=WnVq-iyBeznu) | 99–107 | Standardize breast cancer features, train and evaluate LogisticRegression, and save the model, scaler, and feature names with joblib. |
| Not recorded | [Gradio frontend — Cancer AI](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=xaU7o0vhgywa) | 108–111 | CSV upload and validation, logistic regression predictions, probability charts, patient results, confidence flags, and CSV download. |
| Not recorded | [Artificial neural network (ANN / MLP)](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=5WmD-SUm_KnA) | 112–113 | Fake/real news classification using TF-IDF (5,000 features) and MLPClassifier with hidden layers (64, 32), ReLU, Adam, and early stopping; evaluate classification metrics. |
| Not recorded | [K-means clustering](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=wARXsDfXBV7m) | 114–115 | Load 2,000 Hugging Face news records, build TF-IDF features, form two clusters, calculate ARI/silhouette scores, visualize with PCA, and inspect top cluster terms. |

## Preprocessing exercise index

| Exercise | Topic | Implemented work |
| --- | --- | --- |
| [Q1](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=PBcSqu4FNzis) | Load and inspect data | Read news data from Google Sheets; display head, info, and descriptive statistics. |
| [Q2](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=Jder1uWwO8CU) | Dataset structure | Count rows and columns; inspect data types and missing values. |
| [Q3](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=TdXm5LnjPmUj) | Record inspection | Display first and last records; the random-sample cell currently references `df.sample` without calling it. |
| [Q4](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=5b3kzhF5Qb57) | Missing values | Count missing values and percentages; drop rows with missing text into `df_clean`. |
| [Q5](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=cPZXwIXNR0Rj) | Duplicates | Count duplicate records; the removal line is commented out. |
| [Q6](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=_bzE5A6TSyja) | Outlier detection | Create word/character counts, draw box plots, and detect word-count outliers using IQR. |
| [Q7](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=zufrOXNBW2lf) | Outlier handling | Create `df_trimmed` by removing rows above the IQR upper bound. |
| [Q8](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=K2CfOJNfXPqJ) | Categorical encoding | Apply LabelEncoder and OneHotEncoder to labels. |
| [Q9](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=0MgvC7miYjnt) | Feature scaling | Demonstrate MinMaxScaler and StandardScaler on word/character counts. |
| [Q10](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=6AOMjG57adnx) | Feature selection | Plot correlations and flag/drop features with absolute correlation above 0.85. |
| [Q12](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=wRFKDAk6J1IV) | Feature engineering | Create word count, character count, average word length, and title word count. |
| [Q13](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=jtu0VYU7KQK-) | Data types | Convert labels to category and word counts to float. |
| [Q14](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=sNWPp4aNKXgC) | Text cleaning | Lowercase text; remove URLs, HTML, punctuation, and extra whitespace. |
| [Q15](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=m-gPB3m1KbfL) | Train/test split | Make an 80/20 stratified split with random state 42. |
| [Q16](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=IOrOGZogKlYZ) | Class balancing | Apply SMOTE to training features and labels. |
| [Q17](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=-zaDgCQIKo7T) | Distribution plots | Compare word/character-count histograms before and after SMOTE. |
| [Q18](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=Fnb4kRhWKu0a) | Preprocessing summary | Build a before/after summary table. |
| [Q19](https://colab.research.google.com/drive/12MHY1a_TQadI9zLf-yElJ8kxa-G8KA5O#scrollTo=SNocfM-eK60t) | Export | Save `cleaned_preprocessed_dataset.csv`. |

The source notebook skips **Q11**; numbering above follows the notebook.

## Files

| File | Purpose |
| --- | --- |
| [AI_LAB_1ipynb.ipynb](AI_LAB_1ipynb.ipynb) | Latest Colab notebook; contains all sections indexed above. |
| [ai_lab_1ipynb.py](ai_lab_1ipynb.py) | Earlier Python export of the preprocessing exercises only; adapted to use the included CSV locally. |
| [cleaned_preprocessed_dataset.csv](cleaned_preprocessed_dataset.csv) | Exported news dataset and engineered features. |
| [requirements.txt](requirements.txt) | Local preprocessing-script dependencies. |

## Opening and running the work

Open the notebook in Colab and use the section links above. Regression requires **`linear_regression_dataset_1000.xlsx`**, which is referenced in the notebook but is not included in this repository. The notebook also uses Google Sheets and Hugging Face as online data sources. Its additional sections use `openpyxl` (Excel), `gradio`, and `datasets`; these are not listed in the current preprocessing requirements.

Some sections reuse variables such as `df`, `X`, and `y` for different datasets. In particular, ANN expects the news dataset, whereas preceding classification sections replace `df` with breast cancer data. Reload the news data before running ANN. The final K-means cell also contains an unfinished `plt.title(...)` string and needs correction before it can run.

To run the earlier preprocessing script locally:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python ai_lab_1ipynb.py
```

For a noninteractive run, use `MPLBACKEND=Agg python ai_lab_1ipynb.py`. The script writes its processed output to `cleaned_preprocessed_dataset.csv` in the current directory.
