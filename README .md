# 🤖 Machine Learning Projects — Code Alpha Internship

> **Author:** Vijay Wargiya  
> **Internship:** Code Alpha Data Science Internship  
> **Repo:** [vijaywargiyavivek160305/tasks](https://github.com/vijaywargiyavivek160305/tasks)

A collection of 4 end-to-end machine learning projects covering classification, data analysis, and regression — built with Python, scikit-learn, pandas, and matplotlib.

---

## 📁 Project Structure

```
tasks/
├── task1/
│   ├── Task1_Iris_Classification.ipynb
│   └── iris (1).csv
├── task2/
│   ├── Task2_Unemployment_Analysis.ipynb
│   └── unemployment.csv
├── task3/
│   ├── Task3_Car_Price_Prediction.ipynb
│   └── CarPrice.csv
├── task4/
│   ├── Task4_Sales_Prediction.ipynb
│   └── advertising.csv
└── README.md
```

---

## 🌸 Task 1 — Iris Flower Classification

**Notebook:** `task1/Task1_Iris_Classification.ipynb`  
**Dataset:** `iris (1).csv` — 150 samples of Iris flowers (setosa, versicolor, virginica)

### Objective
Classify Iris flower species based on sepal and petal measurements using multiple ML algorithms.

### Features
| Column | Description |
|--------|-------------|
| sepal_length | Sepal length (cm) |
| sepal_width | Sepal width (cm) |
| petal_length | Petal length (cm) |
| petal_width | Petal width (cm) |
| species | Target: setosa / versicolor / virginica |

### Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

### Highlights
- Pairplot and correlation heatmap for EDA
- 5-fold cross-validation for each model
- Confusion matrix and classification report for the best model
- Feature importance from Random Forest
- Single-sample prediction demo

---

## 📊 Task 2 — Unemployment Analysis with Python

**Notebook:** `task2/Task2_Unemployment_Analysis.ipynb`  
**Dataset:** `unemployment.csv` — Indian state-wise unemployment data (Jan–Nov 2020)

### Objective
Analyze unemployment trends across Indian states and study the impact of Covid-19 on employment.

### Features
| Column | Description |
|--------|-------------|
| Region | Indian state/region |
| Date | Date of observation |
| Estimated Unemployment Rate (%) | Unemployment rate |
| Estimated Employed | Number of employed people |
| Estimated Labour Participation Rate (%) | Labour participation rate |
| longitude / latitude | Geographic coordinates |

### Highlights
- Pre-Covid vs Covid Peak vs Recovery phase comparison
- Region × Month heatmap to identify hotspots
- Scatter analysis: unemployment vs labour participation
- Key policy insights on the Covid-19 impact

---

## 🚗 Task 3 — Car Price Prediction

**Notebook:** `task3/Task3_Car_Price_Prediction.ipynb`  
**Dataset:** `CarPrice.csv` — 205 cars with 26 attributes

### Objective
Predict car prices using car specifications like engine size, horsepower, body type, and brand.

### Features (Key)
| Column | Description |
|--------|-------------|
| CarName | Car brand and model |
| horsepower | Engine horsepower |
| enginesize | Engine displacement |
| curbweight | Car weight |
| highwaympg | Highway fuel efficiency |
| price | Target variable |

### Models Used
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### Highlights
- Brand name extraction and typo correction from `CarName`
- Correlation heatmap across all 26 features
- Actual vs Predicted plot and residual analysis
- Feature importance ranking from the best model

---

## 💰 Task 4 — Sales Prediction

**Notebook:** `task4/Task4_Sales_Prediction.ipynb`  
**Dataset:** `advertising.csv` — 200 records of ad spend vs sales

### Objective
Predict product sales based on advertising budgets across TV, Radio, and Newspaper channels.

### Features
| Column | Description |
|--------|-------------|
| TV | TV advertising budget ($000s) |
| Radio | Radio advertising budget ($000s) |
| Newspaper | Newspaper advertising budget ($000s) |
| Sales | Target: units sold |

### Highlights
- ROI analysis per advertising channel
- Feature engineering on ad spend ratios
- Marketing budget recommendations based on model insights
- Future sales prediction for custom ad budgets

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical computations |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical plots and heatmaps |
| `scikit-learn` | ML models, preprocessing, evaluation |

---

## ⚙️ Setup & Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/vijaywargiyavivek160305/tasks.git
   cd tasks
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. Open any notebook from `task1/`, `task2/`, `task3/`, or `task4/` and run all cells.

---

## 📬 Contact

**Vijay Wargiya**  
GitHub: [@vijaywargiyavivek160305](https://github.com/vijaywargiyavivek160305)
