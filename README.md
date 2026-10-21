# Francesco Di Stasio - Data Analyst Portfolio

## About me

Hi, I’m Francesco, a Data Analyst and Lecturer based in Germany, with a PhD in Electrical, Electronics and Communications Engineering.
My background spans academic research, telecommunications, and teaching, with a focus on statistical modeling and data analysis.
I use Python, SQL, MATLAB, and Power BI to explore complex datasets and communicate meaningful insights.
This portfolio showcases my projects in data analytics, machine learning, and visualization.

Read here my [CV](./CV.pdf)

### TV Show Cancellation: Exploring First-Season Risk Factors

**Goal:** Investigate which first-season characteristics are associated with TV show cancellation.

**Description:** A two-notebook project combining IMDb, TMDB, and TVMaze data. The first notebook integrates and cleans the sources, engineering features such as episode rating trends, voting activity, and release strategy [here](TV_Shows_project_getDataset.ipynb). The second performs exploratory analysis and builds a logistic regression classifiern [here](TV_shows_project.ipynb).

**Skills:** Data integration, data cleaning, API data collection, feature engineering, exploratory data analysis, binary classification, model evaluation.

**Technology:** Python, pandas, NumPy, Requests, Matplotlib, Seaborn, scikit-learn, Jupyter Notebook.

**Results:** Built a dataset of 2,143 TV shows before final preprocessing. Higher first-season ratings showed a weak negative correlation with cancellation. The baseline model achieved 80% test accuracy but only 1% recall for canceled shows, highlighting poor minority-class detection and the need for further model refinement.


### Brazilian E-Commerce: Delivery Performance & Customer Satisfaction

An analysis of the public Olist dataset using Python to explore delivery delays, customer reviews, and differences across regions, product categories, and sellers.

**Project Notebooks**
1. [Data Preparation](./Brazilian_E-Commerce_dataPrep.ipynb) — Data cleaning, type conversion, and quality checks.
2. [Data Integration](./Brazilian_E-Commerce_dataIntegration.ipynb) — Dataset merging and order-level aggregation.
3. [Exploratory Data Analysis](./Brazilian_E-Commerce_EDA.ipynb) — Delivery metrics, visualizations, and business insights.

**Key Finding**: Late deliveries were associated with substantially more low ratings: 62.37% versus 9.27% for on-time orders.

**Tools:** Python, pandas, NumPy, Matplotlib, Seaborn.
