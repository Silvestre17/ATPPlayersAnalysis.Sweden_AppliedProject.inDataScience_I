# 🎾 ATP Players Analysis - Sweden 🇸🇪

<p align="center">
  <img src="./img/Banner.png" alt="ATP Tennis Data Analysis Banner" width="800">
</p>

## 📝 Description

This project performs a comprehensive analysis of an **ATP (Association of Tennis Professionals)** tennis dataset, with a specific focus on matches played in **Sweden** 🇸🇪. The workflow covers the entire data science lifecycle, from initial data exploration and web scraping to feature engineering and the application of machine learning models to predict the number of sets in a match.

<p align="center">
    <img src="./img/ATP_Tour_logo.svg.png" alt="ATP" width="200">
</p>

<p align="center">
    <!-- Project Links -->
    <a href="https://github.com/Silvestre17/ATPPlayersAnalysis.Sweden_AppliedProject.inDataScience_I"><img src="https://img.shields.io/badge/Project_Repo-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo"></a>
</p>

## ✨ Objective

The main objective is to leverage data science techniques to:

*   **Explore and understand** the provided ATP tennis dataset.
*   **Clean and prepare** the data for analysis and modeling.
*   **Predict the number of sets** played in matches held in *Sweden*, using various features related to players and tournaments.

## 📚 Context

This project was completed as part of the **Projeto Aplicado a Ciência de Dados I** (*Applied Project in Data Science I*) course in the **[Licenciatura em Ciência de Dados](https://www.iscte-iul.pt/degree/code/0322/bachelor-degree-in-data-science)** (*Bachelor Degree in Data Science*) at **ISCTE-IUL** in academy year 2022/2023 (2nd semester of 2nd year).

It involved **Weekly Presentations** to showcase progress and a **[`Final Presentation`](./Apresentação_Final_PACDI_Grupo2_ATP.pdf)** to summarize the project's findings and results.
These presentations can be found in the [**`./ApresentacoesSemanais`**](./ApresentacoesSemanais) folder, 

Additionally, the **Final Project Report** is available in the [**`Report`**](./Relatório_PACDI_Grupo2_ATP_Suécia.pdf).


## 🧮 Data Source

*   The core data comes from the official **[ATP Tour](https://www.atptour.com/en/rankings/singles)** website.
    *   The dataset is in **JSON** format and contains information about players, tournaments, matches, and scores.
    *   It was provided as part of the course materials and are the same as the ones used in the **[Armazenamento para Big Data (*Storage for Big Data*) project](https://github.com/Silvestre17/ATP.Tennis_MongoDB-SQL_BigDataStorage)**.

## 🏗️ Project Structure (CRISP-DM)

This project followed the CRISP-DM methodology for data mining. Here's a breakdown of the key activities in each phase:

1.  **Business Understanding:** 💡
    *   Defined the objective: To explore and analyze ATP data and predict the number of sets in Swedish tournaments.
    *   Identified key aspects: Players, tournaments, scores, and match details.

<p align="center">
    <a href="https://www.python.org/">
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    </a>
    <a href="https://pandas.pydata.org/">
        <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
    </a>
</p>

1.  **Data Understanding:** 🔍
    *   Loaded and inspected the JSON dataset.
    *   Identified data quality issues: missing values, inconsistent formats, and need for external data.
    *   Explore and analyze data related to ATP tennis tournaments, player attributes, and match results.
    *   Identify key statistics and patterns within the data.
    *   Create interactive dashboards using Power BI to visualize the results and provide a powerful tool for exploring the data.

<p align="center">
    <a href="https://www.numpy.org/">
        <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
    </a>
     <a href="https://www.matplotlib.org/">
        <img src="https://img.shields.io/badge/Matplotlib-D3D3D3?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib" />
    </a>
    <a href="https://www.seaborn.pydata.org/">
        <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn" />
    </a>
</p>

1.  **Data Preparation:** 🛠️
    *   **Data Cleaning:** Handled missing values, standardized text, and fixed inconsistencies.
    *   **Feature Engineering:** Created new features from existing ones (e.g., age difference, player hand).
	*   **Web Scraping:** Used `Beautiful Soup` and `Selenium` to obtain missing player information like birthdates and heights from the ATP website.

<p align="center">
    <a href="https://www.beautifulsoup.org/">
        <img src="https://img.shields.io/badge/BeautifulSoup-59666C?style=for-the-badge&logo=beautifulsoup&logoColor=white" alt="Beautiful Soup" />
    </a>
    <a href="https://www.selenium.dev/">
        <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium" />
    </a>
</p>

4.  **Modeling:** 🤖
    *   Tested several supervised classification algorithms: KNN, Logistic Regression, Decision Tree, and Random Forest.
    *   Used Cross-Validation to evaluate model performance.
    *   Tuned hyperparameters to optimize model performance.

<p align="center">
    <a href="https://www.Scikit-Learn.org/">
        <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
    </a>
</p>

5.  **Evaluation:** ✅
    *   Evaluated models using metrics such as accuracy, precision, recall, F1-score, and AUC.
    *   Analyzed the best model to understand feature importance.

6.  **Deployment:** 🚀
	*   Developed data visualizations in Power BI for further analysis.

<p align="center">
    <a href="https://powerbi.microsoft.com/">
        <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=white" alt="PowerBI" />
    </a>
</p>

<br>

## 📈 Power BI Dashboard

<p align="center">
  <img src="./img/PowerBI.png" alt="Power Bi Overview" width="800">
</p>


## 📚 Conclusion

This project provided valuable experience in data exploration, cleaning, and modeling within the context of tennis data. While the predictive models did not achieve high accuracy, the process of **data preparation** and **feature engineering** was insightful.

Feel free to explore the code and data for more details! 🎾

## 👥 Team Members (Group 2)

*   **André Silvestre** (Nº 104532)
*   **Diogo Catarino** (Nº 104745)
*   **Francisco Gomes** (Nº 104944)
*   **Rita Matos** (Nº 104936)

---

## 🇵🇹 Note

This project was developed using Portuguese from Portugal.
