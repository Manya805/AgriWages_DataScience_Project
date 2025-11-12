🌾 Agricultural Wages Analysis and Prediction Dashboard
-------------------------------------------------------

This project analyzes agricultural wage patterns across Indian states and predicts future wage trends using various machine learning and forecasting techniques.\
It includes **Exploratory Data Analysis (EDA)**, **classification & regression models**, and a **Streamlit-based interactive dashboard** for visualization and forecasting.

* * * * *

### 📁 Project Structure
```
📦 Agricultural_Wages_Project
├── agri_wages_08_06_2022.csv              # Original dataset
├── cleaned_agri_wages.csv                 # Cleaned and preprocessed dataset
├── app.py                                 # Streamlit dashboard app
├── EDA_AgriWages.ipynb                    # Exploratory Data Analysis
├── EDA_AgriWages_KNN.ipynb                # K-Nearest Neighbors classifier
├── EDA_AgriWages_MLR.ipynb                # Multiple Linear Regression
├── EDA_AgriWages_SVM_Classification.ipynb # SVM classification
├── DecisionTree.ipynb                     # Decision Tree model
├── RandomForest.ipynb                     # Random Forest model
├── LogisticReg.ipynb                      # Logistic Regression model
├── SARIMA.ipynb                           # Time Series forecasting (SARIMA)
└── README.md                              # Project documentation
```
* * * * *

### 📂 Dataset Link

Access the dataset used in this project here:  
[DBT District-Wise Performance — India Data Portal](https://indiadataportal.com/p/direct-benefit-transfer/r/cabinet-dbtbharat_dbt_performance-dt-ot-aaa)

> *Note:* This dataset contains district-wise direct benefit transfer (DBT) performance metrics across India.  
> It was obtained from the India Data Portal, under the “Direct Benefit Transfer” category.


### 🚀 Features

-   **Comprehensive EDA:** Explore agricultural wage trends by state, gender, and labour type.

-   **Regression Models:** Predict average monthly wages using multiple linear regression.

-   **Classification Models:** Classify wages into categories (Low, Medium, High) using Logistic Regression, KNN, SVM, Decision Tree, Random Forest, and XGBoost.

-   **Forecasting:** Predict future wage trends for each state using Prophet and SARIMA models.

-   **Interactive Dashboard:** Visualize trends, correlations, and model outputs in real time through Streamlit.

* * * * *

### 🧠 Machine Learning Models Used

| Model Type | Technique | Purpose |
| --- | --- | --- |
| Regression | Multiple Linear Regression | Predict numerical wage values |
| Classification | Logistic Regression, KNN, SVM, Decision Tree, Random Forest, XGBoost | Categorize wages as Low/Medium/High |
| Neural Network | ANN | Non-linear wage prediction |
| Time Series | SARIMA, Prophet | Forecast future wage trends |

* * * * *

### 🧩 Technologies Used

-   **Languages:** Python

-   **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, prophet, statsmodels

-   **Framework:** Streamlit (for the dashboard)

-   **Tools:** Jupyter Notebook, GitHub

* * * * *

### ⚙️ Setup Instructions

#### 1\. Clone the repository

`git clone https://github.com/<your-username>/Agricultural-Wages-Project.git
cd Agricultural-Wages-Project`

#### 2\. Install dependencies

`pip install -r requirements.txt`

If you don't have a `requirements.txt` yet, create one with:

`pip freeze > requirements.txt`

#### 3\. Run the Streamlit Dashboard

`streamlit run app.py`

#### 4\. Explore

-   Use the sidebar to select states, models, and forecasting periods.

-   Navigate between **EDA**, **Regression**, **Classification**, **Clustering**, **Tree-based models**, **XGBoost**, and **Forecasting** tabs.

* * * * *

### 📊 Dataset Description

The dataset contains agricultural wage information across different Indian states and districts.

| Column Name | Description |
| --- | --- |
| state_name | Name of the Indian state |
| district_name | Name of the district (if available) |
| gender | Male/Female labour classification |
| labour_type | Type of agricultural labour |
| monthly_average_wage | Average monthly wage (₹) |
| annual_average_wage | Average annual wage (₹) |
| month / year | Time period of data record |

* * * * *

### 📈 Key Insights

-   Wage levels vary significantly by **state, gender, and labour category**.

-   Seasonal fluctuations influence monthly wages.

-   States with higher mechanization show consistent wage patterns.

-   Forecasting models like Prophet and SARIMA can effectively predict short-term wage trends.

* * * * *

### 🖥️ Output Preview

-   **EDA:** Distribution plots, wage trends, and correlation heatmaps.
-   <img width="957" height="571" alt="0" src="https://github.com/user-attachments/assets/60d07988-76dc-42f0-a186-7b339fd1bb8a" />
<img width="603" height="460" alt="0" src="https://github.com/user-attachments/assets/a52308cc-dde1-4b69-8285-b5fdb542acc1" />


-   **Regression & Classification:** Model performance metrics, accuracy reports, and confusion matrices.
-   <img width="1009" height="552" alt="unnamed" src="https://github.com/user-attachments/assets/e4bac2b4-e585-45af-a484-1be515457ce2" />
<img width="617" height="473" alt="unnamed" src="https://github.com/user-attachments/assets/c9fc40d4-3afc-4108-9edc-e20bb7b8d828" />
<img width="575" height="384" alt="unnamed" src="https://github.com/user-attachments/assets/c5bb4ef2-c2bf-4bd9-87c7-071640560389" />

-   **Forecasting:** Future wage predictions plotted against actual trends.
-   <img width="1350" height="600" alt="unnamed" src="https://github.com/user-attachments/assets/c7478587-5049-48eb-975e-38397e9378c4" />
<img width="489" height="554" alt="unnamed" src="https://github.com/user-attachments/assets/059ad9aa-aad6-4389-adc1-984fa0361fa6" />


-   **Dashboard:** Interactive visualizations and model training modules.
<img width="1731" height="822" alt="unnamed" src="https://github.com/user-attachments/assets/83a63ac7-d871-4c07-b606-792dd38990dd" />

* * * * *

### 🔮 Future Enhancements

-   Incorporate **geospatial analysis** for district-level visualizations.

-   Add **automated model evaluation** and **hyperparameter tuning**.

-   Expand dataset to include **more years and agricultural categories**.

-   Deploy dashboard online using **Streamlit Cloud** or **Render**.
