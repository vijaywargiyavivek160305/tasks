🤖 Machine Learning Projects — Code Alpha Internship


Author: Vijay Wargiya

Internship: Code Alpha Data Science Internship

Repo: vijaywargiyavivek160305/tasks



A collection of 4 end-to-end machine learning projects covering classification, data analysis, and regression — built with Python, scikit-learn, pandas, and matplotlib.


📁 Project Structure

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


🌸 Task 1 — Iris Flower Classification

Notebook: task1/Task1_Iris_Classification.ipynb

Dataset: iris (1).csv — 150 samples of Iris flowers (setosa, versicolor, virginica)

Objective

Classify Iris flower species based on sepal and petal measurements using multiple ML algorithms.

Features

ColumnDescriptionsepal_lengthSepal length (cm)sepal_widthSepal width (cm)petal_lengthPetal length (cm)petal_widthPetal width (cm)speciesTarget: setosa / versicolor / virginica

Models Used


Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)


Highlights


Pairplot and correlation heatmap for EDA
5-fold cross-validation for each model
Confusion matrix and classification report for the best model
Feature importance from Random Forest
Single-sample prediction demo



📊 Task 2 — Unemployment Analysis with Python

Notebook: task2/Task2_Unemployment_Analysis.ipynb

Dataset: unemployment.csv — Indian state-wise unemployment data (Jan–Nov 2020)

Objective

Analyze unemployment trends across Indian states and study the impact of Covid-19 on employment.

Features

ColumnDescriptionRegionIndian state/regionDateDate of observationEstimated Unemployment Rate (%)Unemployment rateEstimated EmployedNumber of employed peopleEstimated Labour Participation Rate (%)Labour participation ratelongitude / latitudeGeographic coordinates

Highlights


Pre-Covid vs Covid Peak vs Recovery phase comparison
Region × Month heatmap to identify hotspots
Scatter analysis: unemployment vs labour participation
Key policy insights on the Covid-19 impact



🚗 Task 3 — Car Price Prediction

Notebook: task3/Task3_Car_Price_Prediction.ipynb

Dataset: CarPrice.csv — 205 cars with 26 attributes

Objective

Predict car prices using car specifications like engine size, horsepower, body type, and brand.

Features (Key)

ColumnDescriptionCarNameCar brand and modelhorsepowerEngine horsepowerenginesizeEngine displacementcurbweightCar weighthighwaympgHighway fuel efficiencypriceTarget variable

Models Used


Linear Regression
Ridge Regression
Lasso Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor


Highlights


Brand name extraction and typo correction from CarName
Correlation heatmap across all 26 features
Actual vs Predicted plot and residual analysis
Feature importance ranking from the best model



💰 Task 4 — Sales Prediction

Notebook: task4/Task4_Sales_Prediction.ipynb

Dataset: advertising.csv — 200 records of ad spend vs sales

Objective

Predict product sales based on advertising budgets across TV, Radio, and Newspaper channels.

Features

ColumnDescriptionTVTV advertising budget ($000s)RadioRadio advertising budget ($000s)NewspaperNewspaper advertising budget ($000s)SalesTarget: units sold

Highlights


ROI analysis per advertising channel
Feature engineering on ad spend ratios
Marketing budget recommendations based on model insights
Future sales prediction for custom ad budgets



🛠️ Tech Stack

LibraryPurposepandasData loading and manipulationnumpyNumerical computationsmatplotlibData visualizationseabornStatistical plots and heatmapsscikit-learnML models, preprocessing, evaluation


⚙️ Setup & Run


Clone the repository


bash   git clone https://github.com/vijaywargiyavivek160305/tasks.git
   cd tasks


Install dependencies


bash   pip install pandas numpy matplotlib seaborn scikit-learn


Launch Jupyter Notebook


bash   jupyter notebook


Open any notebook from task1/, task2/, task3/, or task4/ and run all cells.



📬 Contact

Vijay Wargiya

GitHub: @vijaywargiyavivek160305
