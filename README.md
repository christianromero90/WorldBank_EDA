# World Bank EDA 

Final project for "Python for Business Analytics" class of my MsBa program at HIBS. It focused on exploring World Bank data consisting of 41 indicators (columns) on 217 countries (rows). This report focuses on the North America/Latin American region of the dataset. The purpose of the project was to conduct thorough EDA and share insightful conclusions. 

---
### Project Overview
In this project, teams are tasked with conducting an analysis utilizing data from the World Bank. Each student group shall receive a dataset on countries in one region of the world at random and are expected to:

- Conduct an exploratory data analysis using Python
- Formulate a strategy for missing values and identifying potential outliers
- Develop a Jupyter Notebook on their process and findings (with ample use of markdown) 

---
### Analysis Requirements

Using 1,000 - 1,500 words of markdown:

- Introduce your region from a non-technical perspective (culture, world-famous aspects, etc.). 
- Select one country from your region that you feel best represents it "on average". Include the rationale for your choice and support it with Python code.
- Identify any obscure findings in the data. In other words "Does the data accurately reflect the region? Can your region's numbers be trusted?"
- Explain your strategy for missing values, as well as your strategy for identifying outliers.
- Select the Top 5 features (i.e. columns) of the dataset that best exemplify your region. In other words, "What makes your region unique when compared to the rest of the world?"
- Support your findings with domain knowledge (i.e. research from external sources). Make sure to site your sources.

---
### Packages:

- Pandas
- Numpy
- Matplotlib
- Seaborn

---
### Summary Findings:

The North America/Latin American region is probably one of the most diverse regions worldwide. This region includes multiple countries: from Canada in the north, to Argentina in the south. Due to strong differences in cultures and languages, there is another way to group these countries: All countries from Mexico to the south are denominated as Latin American, while The United States and Canada are grouped as Anglo-America.


#### Missing Values & Accuracy Assessment
- According to the IMF, Bermuda was the only country in our region that substantially missed information
- this might be because it is not subscribed to the SDDS (Special data dissemination standard). This standard was established by the IMF for member countries that have or that might seek access to international capital markets, to guide them in providing their economic and financial data to the public
- Imputation techniques were implemented for some of the missing values for different countries depending on their distribution. Due to skewness of data, the median was the generally selected imputation method.

#### Representative Country: 
- **Mexico** is the country which best represents the North America/LatinAmerica region on average. It has the least missing values and has the least variation to the mean of the different indicators, even though the country has been reported as an outlier in some indicators. 

#### Five Unique Indicators: 
- Maternal Mortality Rate (Below world average),
- GDP Per Person Employed (below world average),
- Net ODA received per capita (below world average),
- GNI per capita (below world average)
- Incidence of Tuberculosis (below world average)
