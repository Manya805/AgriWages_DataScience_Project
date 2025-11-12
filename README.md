🌾 Agricultural Wages Analysis and Prediction Dashboard
-------------------------------------------------------

This project analyzes agricultural wage patterns across Indian states and predicts future wage trends using various machine learning and forecasting techniques.It includes **Exploratory Data Analysis (EDA)**, **classification & regression models**, and a **Streamlit-based interactive dashboard** for visualization and forecasting.

### 📁 Project Structure

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   📦 Agricultural_Wages_Project  ├── agri_wages_08_06_2022.csv           # Original dataset  ├── cleaned_agri_wages.csv              # Cleaned and preprocessed dataset  ├── app.py                              # Streamlit dashboard app  │  ├── EDA_AgriWages (2).ipynb             # Exploratory Data Analysis  ├── EDA_AgriWages_KNN.ipynb             # K-Nearest Neighbors classifier  ├── EDA_AgriWages_MLR.ipynb             # Multiple Linear Regression  ├── EDA_AgriWages_SVM_Classification.ipynb # SVM classification  ├── DecisionTree.ipynb                  # Decision Tree model  ├── RandomForest.ipynb                  # Random Forest model  ├── LogisticReg.ipynb                   # Logistic Regression model  ├── ANN.ipynb                           # Artificial Neural Network model  ├── SARIMA.ipynb                        # Time Series forecasting (SARIMA)  └── README.md                           # Project documentation   `

### 🚀 Features

*   **Comprehensive EDA:** Explore agricultural wage trends by state, gender, and labour type.
    
*   **Regression Models:** Predict average monthly wages using multiple linear regression.
    
*   **Classification Models:** Classify wages into categories (Low, Medium, High) using Logistic Regression, KNN, SVM, Decision Tree, Random Forest, and XGBoost.
    
*   **Forecasting:** Predict future wage trends for each state using Prophet and SARIMA models.
    
*   **Interactive Dashboard:** Visualize trends, correlations, and model outputs in real time through Streamlit.
    

### 🧠 Machine Learning Models Used

Model TypeTechniquePurposeRegressionMultiple Linear RegressionPredict numerical wage valuesClassificationLogistic Regression, KNN, SVM, Decision Tree, Random Forest, XGBoostCategorize wages as Low/Medium/HighNeural NetworkANNNon-linear wage predictionTime SeriesSARIMA, ProphetForecast future wage trends

### 🧩 Technologies Used

*   **Languages:** Python
    
*   **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, prophet, statsmodels
    
*   **Framework:** Streamlit (for the dashboard)
    
*   **Tools:** Jupyter Notebook, GitHub
    

### ⚙️ Setup Instructions

#### 1\. Clone the repository

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   git clone https://github.com//Agricultural-Wages-Project.git  cd Agricultural-Wages-Project   `

#### 2\. Install dependencies

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   pip install -r requirements.txt   `

If you don’t have a requirements.txt yet, create one with:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   pip freeze > requirements.txt   `

#### 3\. Run the Streamlit Dashboard

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   streamlit run app.py   `

#### 4\. Explore

*   Use the sidebar to select states, models, and forecasting periods.
    
*   Navigate between **EDA**, **Regression**, **Classification**, **Clustering**, **Tree-based models**, **XGBoost**, and **Forecasting** tabs.
    

### 📊 Dataset Description

The dataset contains agricultural wage information across different Indian states and districts.

Column NameDescriptionstate\_nameName of the Indian statedistrict\_nameName of the district (if available)genderMale/Female labour classificationlabour\_typeType of agricultural labourmonthly\_average\_wageAverage monthly wage (₹)annual\_average\_wageAverage annual wage (₹)month / yearTime period of data record

### 📈 Key Insights

*   Wage levels vary significantly by **state, gender, and labour category**.
    
*   Seasonal fluctuations influence monthly wages.
    
*   States with higher mechanization show consistent wage patterns.
    
*   Forecasting models like Prophet and SARIMA can effectively predict short-term wage trends.
    

### 🖥️ Output Preview

*   **EDA:** Distribution plots, wage trends, and correlation heatmaps.
    
*   **Regression & Classification:** Model performance metrics, accuracy reports, and confusion matrices.
    
*   **Forecasting:** Future wage predictions plotted against actual trends.
    
*   **Dashboard:** Interactive visualizations and model training modules.
    

### 🔮 Future Enhancements

*   Incorporate **geospatial analysis** for district-level visualizations.
    
*   Add **automated model evaluation** and **hyperparameter tuning**.
    
*   Expand dataset to include **more years and agricultural categories**.
    
*   Deploy dashboard online using **Streamlit Cloud** or **Render**.
