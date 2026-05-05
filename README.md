# DSA-210-Project

# Final Proposal Report updated after the feedback (bias avoided version)

This project aims to analyze the factors that influence tourism demand across countries,
with a specific focus on whether tourists prioritize cost or safety when choosing travel
destinations. The motivation behind this project comes from a simple but interesting
question: when people decide where to travel, do they care more about acordability or how
safe a destination is?
The data for this project will be collected from publicly available datasets on Kaggle. A
tourism dataset will be used as the main variable, but instead of using total international
tourist arrivals, normalized measures such as tourists per capita or tourism contribution to
GDP (%) will be used to avoid bias toward larger countries. In addition, a cost of living
dataset and a safety index dataset will be included to represent economic conditions and
safety levels across countries. These additional datasets will be used to enrich the analysis
and allow for a more meaningful comparison, as suggested in the project guidelines.
All datasets are country-based and will be combined using the country variable. The data
mainly consists of numerical indicators such as tourism intensity measures, cost of living
index, and safety index. The datasets are expected to include data for many countries
(around 50 or more), which should provide enough observations for analysis. Special
attention will be given to ensuring that all datasets correspond to the same or closely
aligned time periods, so that the analysis remains consistent and meaningful.
The data will be collected by downloading CSV files and processed in Python. After
combining the datasets, some basic data cleaning and preparation steps will be applied.
The project will then use data analysis and visualization techniques to explore the
relationships between variables. Overall, the goal is to understand whether cost or safety
plays a more significant role in attracting tourists and to interpret the findings accordingly.


# Machine Learning
In this phase of the project, I applied machine learning methods to analyze the relationship between tourism demand and country-level indicators such as cost of living, safety, and overall quality of life. Based on the feedback, the analysis was extended from a single year (e.g., 2015) to a multi-year dataset, introducing a temporal dimension and improving the robustness of the results. The target variable used is tourism_gdp_ratio, which normalizes tourism performance across countries and reduces bias toward larger economies. Two models, Linear Regression and Random Forest Regressor, were implemented to capture both interpretable relationships and potential non-linear patterns. The features used in the models include Cost of Living Index, Safety Index, Quality of Life Index, Purchasing Power Index, Health Care Index, Pollution Index, Property Price to Income Ratio, Traffic Commute Time Index, Inflation, Unemployment, and Year (added to capture temporal trends). The models were evaluated using MAE (Mean Absolute Error), RMSE (Root Mean Squared Error), and R² Score, allowing for a comprehensive comparison of prediction accuracy and overall model performance.


