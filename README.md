# Welcome to Sophie's Data Science Portfolio! 👋

## Bio
* Working at DuPont as a Data & Systems Analyst in Product Stewardship and Regulatory, participating in the Supply Chain Rotational Program.
* Pursuing a Master of Information and Data Science at UC Berkeley and expected graduation in May 2023.
* Currently taking NLP with Deep Learning (W266) and Machine Learning at Scale (W261).
* B.S. in Chemical Engineering and minor in Operations and Supply Chain Management from Carnegie Mellon Unviersity, Class of 2021.

## <span style="color:DarkGrey"> **Predicting Flight Delays** (Upcoming)</span>
In order for airlines to provide positive customer experience and respond quickly to flight delays, it is important to that coordinators are notified as soon as possible. This project uses flights data from the US Department of Transportation and weather data from the National Oceanic and Atmospheric repository to build a machine learning model predicting flight delays two hours ahead of departure. The large datasets will be stored in Databricks. The processing pipeline and machine learning model will be built using Spark and Python.

## [**Metagenome Environment Classification**](https://github.com/sophieyeh256/W207_Final_Project)
### _Decision Tree, XGB, Neural Net, SHAP, Biotech_
Environmental metagenomics is the study of organisms in a microbial community based on analyzing the DNS within an environmental sample. Examples include profiling microbial populations in water samples taken from deep ocean vents or in the human gut that protect the host from pathogens. Environmental metagenomics study data are used for agricultural microbiome analysis, ecological remediation, or other biological investigations. At the Joint Genome  Institute, microbiologists have sequenced metagenome samples to assemble sets of protein families and classified them by environment. **In order to open research to identify the origins of unknown microbial samples and better understand the underlying functions of protein families, this project aims to create a classifier that determines the environment of a microbial sample based on its composition of protein families.** Exploratory data analysis was conducted and a baseline decision tree model was used to benchmark against XGBoost and Convolutional Neural Network models. After hyperparameter tuning using Optuna, the XGBoost model achieved an F1-score of 93.08% and the Convolutional Neural Network achieved an F1-score of 92.30%, which is a significant improvement from the baseline decision tree's F1-score of 89.69%. Although class imbalance greatly limited our scoring and performance, SHAP analysis demonstrated that our XGBoost model is able to identify dominant protein families in an environment that have key functionalities.


## [**A Descriptive Analysis of Climate Change Accountability**](https://github.com/sophieyeh256/w200_project2_bluhm_kim_Yeh)
### _Data Visualization, Matplotlib, Plotly, Climate_
One major debate at the 2021 UN Climate Change Conference is whether the world's wealthiest nations are the most responsible 
for global warming and whether they should compensate poorer nations for increasingly severe weather. To better understand the biases and implications of this debate, this project provides aesthetically pleasing and insightful visualizations to compare the severe weather and pollution experience between high- and low-polluting countries in the world.


## [**ACME Delivery Analytics**](https://github.com/sophieyeh256/DataEng_SQL/blob/main/ucb_mids_w205_project_3/Acme%20Delivery%20Strategy.pdf)
### _SQL, Neo4J, Data Engineering, Sales Analytics, Data Visualization_
ACME, a lunch delivery business, is looking into opening more locations in the Bay Area and investing in robots and/or drones in the future. Querying customer, sales, and store data using PostgreSQL, we analyzed the geographic radius of ACME's customer database and their buying frequency. Neo4J was used to query store locations and assess the store locations and their shortest paths using the BERT public transportation system. As part of our recommendations, we identified 3 key BERT stations with high population and degree centrality that can serve as an effective pickup location. Since most orders only involve one item and the majority of the customer base is within 4 miles of stores, we recommend a hybrid approach in future technology investments - starting with using drones and/or robots doing last-mile deliveries to customers in close locations and using BERT pickup locations and other brick-and-mortar stores as departure points.

## [**FIFA Player Market Value Factors**](https://github.com/sophieyeh256/ucb_mids_w203_lab2)
### _R, Linear Regression, Feature Selection, Hypothesis Testing, Large Sample Assumptions, sports_
FIFA is a professional organization that recruits athletes based on a variety of factors recorded in their databasis. 
Our research question is how does a goal keeper's performance, background, and physical attributes affect their market value in football (soccer)?
The aim is to focus hypothesis testing, large sample assumptions, and statistical concepts such as Independent and Identical Distribution, covariation, collinearity, p-values, VIF, and diagnostic plots.  


## [**Did Democratic or Republican voters experience more difficulty voting during the 2020 election?**](https://github.com/sophieyeh256/ucb_mids_w203_lab1)
### _R, Wilcoxon Ranked Sum Test, Hypothesis Testing, politics_
Our analysis takes a detailed look at the dataset from 2020 American National Election Studies by categorizing respondents to appropriate political parties and applying the Wilcoxon Ranked Sum Test to evaluate the null hypothesis that Democratic and Republican voters had equal
difficulty voting in 2020 elections.  


## [**Gym Routine App**](w200_project1_gymroutine)
### _Python, SQLite Tkinter, Web Scraping, Inventory Management, Gym_
Gym fitness is one of the most efficient ways of building muscle but to achieve a proportional body shape, gym-goers plan a routine
that encompasses a variety of muscles. This project uses Spyder to obtain information from a exercise encyclopedia on workouts and
relevant muscle groups. The app interface allows users to plan their routine and view the muscle distribution of their workouts. 
A recommendation function suggests exercises that will even out the muscle distribution of their current workout plan and a sqLite
database is used to store workout exercise information and user routines.

## [**Citadel Terminal Summer 2022 Invitational Competition**](https://github.com/sophieyeh256/terminal-summer22-eiren)
### _Python, Algorithms, Gaming, Team Eiren_
In this competition, teams have one week to develop an algorithm in Python to compete with others in Tower Defense. 
