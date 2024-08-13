# Welcome to My Data Analysis Portfolio

Hello and welcome to my Portfolio! I’m Kathir, Mater's degree Gradute in Economics and a Data analyst with a passion for turning raw data into meaningful insights. This Page showcases a collection of projects that highlight my expertise in data manipulation, statistical analysis, and visualization.

## About This Portfolio

In this Portfolio, you’ll find a range of projects demonstrating my skills in various aspects of data analysis:

- **Data Cleaning and Transformation:** Projects where I’ve tackled messy datasets, performed data wrangling, and prepared data for analysis.
- **Exploratory Data Analysis (EDA):** In-depth explorations to uncover patterns, trends, and key insights.
- **Statistical Analysis:** Applications of statistical methods to derive insights and support data-driven decision-making.
- **Data Visualization:** Creation of compelling visualizations to effectively communicate findings and support decision-making.
- **Predictive Modeling:** Building and evaluating predictive models to forecast trends and outcomes.

Each project in this page includes detailed descriptions, code link, and where applicable, interactive visualizations or dashboards. You can explore the code, analysis, and visualizations to see the methodologies and techniques used to tackle real-world data challenges.

## Key Technologies

I use a variety of tools and technologies in my data analysis work, including:

- **Python:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, BeautifulSoup
- **R Programming**: ggplot2, dplyr, caret, ivreg
- **SQL:** Data extraction and manipulation
- **Excel:** Advanced formulas, pivot tables, and data visualization
- **Tableau/Power BI:** Interactive dashboards and data visualizations

  
## Project 1: Big Mart Sales Prediction 
![](assets/sales-forecasting-metrics-1024x768.jpg)

## Project Overview
Developed a machine learning model to predict sales for various products across Big Mart outlets, using XGBoost Regressor to address challenges in the retail industry such as inventory management and supply chain optimization.

## Dataset
Utilized Kaggle's Big Mart Sales dataset, which includes product and outlet details such as item weight, visibility, type, MRP, outlet size, location, and establishment year.

## Key Steps
- **Data Collection & Processing:** Loaded the dataset into a Pandas DataFrame for initial analysis.
- **Exploratory Data Analysis:** Conducted EDA using Pandas and Seaborn to check for missing values, and understand numerical and categorical features.
- **Data Pre-Processing:** Handled missing values by filling in the mean for `Item_Weight` and the mode for `Outlet_Size`. Applied label encoding to convert categorical variables to numerical values.
- **Model Training & Evaluation:** Split the dataset into training and testing sets. Trained an XGBoost Regressor model, achieving an R-squared value of 0.64 on training data and 0.59 on testing data.

## Outcome
The model provided reasonable sales predictions with some room for improvement, demonstrating its potential for enhancing inventory management and customer satisfaction.

#### For a more indepth breakdown check out my [Github Page](https://github.com/Kathirrodri17/Portfolio-Projects/edit/main/Bigmart%20sales%20prediction/README.md)

## Project 2: COVID-19 Exploratory Data Analysis [Dash Board Link](https://public.tableau.com/views/Covidproject_17226240422510/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
![](assets/Dashboard.PNG)
This project involves an in-depth exploratory data analysis (EDA) of COVID-19 data using SQL, Excel, and Tableau. The goal was to analyze extensive datasets from multiple countries, clean and prepare the data, and create a comprehensive dashboard to summarize key insights.

## Project Overview
Performed exploratory data analysis of global COVID-19 data to uncover key insights and trends. The analysis focused on infection rates, mortality, and vaccination coverage across different countries and regions, culminating in the creation of an interactive Tableau dashboard.

## Tools and Technologies Used
- **SQL:** Utilized Microsoft SQL Server for querying and initial data analysis.
- **Excel:** Used for data cleaning and preparation.
- **Tableau:** Employed for data visualization and dashboard creation.

## Key Steps
1. **Data Exploration and Findings:** Imported and explored data from the `CovidDeaths` table, including metrics such as total cases, new cases, total deaths, and population by location and date.
   
2. **Analysis of Total Deaths vs. Total Cases in India:** Calculated the death percentage in India to assess the severity of COVID-19 in terms of mortality, comparing it with other regions.

3. **Analysis of Total Cases vs. Population:** Examined the percentage of the population infected by COVID-19 in India to evaluate the extent of the spread and the effectiveness of public health measures.

4. **Countries with Highest Infection Rates:** Identified countries with the highest infection rates relative to their populations, highlighting the most affected regions.

5. **Countries with Highest Death Counts:** Found the countries with the highest total death counts to understand the absolute impact of COVID-19.

6. **Death Counts by Continent:** Analyzed continents with the highest total death counts to identify regional disparities in COVID-19's impact.

7. **Global COVID-19 Metrics:** Summarized global metrics, including total cases, total deaths, and death percentage, providing a macro perspective on the pandemic's impact.

8. **Population vs. Vaccination Coverage:** Explored the correlation between total population and vaccination numbers to assess progress towards achieving herd immunity.

9. **Rolling Vaccination Coverage:** Calculated rolling vaccination coverage over time using a Common Table Expression (CTE) to track the pace of vaccination campaigns.

10. **Temporary Tables for Vaccination Analysis:** Created temporary tables to efficiently analyze and store vaccination coverage data, enabling deeper insights into trends.

## Key Insights
- **Trends Over Time:** Identified significant waves of infections and variations in severity over time.
- **Geographical Distribution:** Highlighted hotspots and regions with different infection and death rates.
- **Comparative Analysis:** Compared the effectiveness of responses across countries and correlated vaccination rates with infection rates.

## Conclusion
This project provides a comprehensive exploratory data analysis of COVID-19, offering valuable insights into global and regional impacts, including infection rates, mortality, and vaccination coverage. The interactive Tableau dashboard visualizes these findings, serving as a tool for understanding the pandemic's effects and supporting informed public health decisions.

For an interactive exploration of the data, visit the COVID-19 Dashboard.

## Contact

If you have any questions or feedback, don’t hesitate to reach out. You can connect with me on [LinkedIn](https://www.linkedin.com/in/kathir-jm/) for more about my professional journey and other work.

Thank you for visiting my portfolio. I hope you find the projects interesting and insightful!

---

J.M.Kathir  
[LinkedIn](https://www.linkedin.com/in/kathir-jm/) |  kathirrodriguez@gmail.com

