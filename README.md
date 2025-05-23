# Predicting Restaurant's Rating


## Project Objective
*The primary objective for this project is to develop a machine learning model that helps in predicting the rating a restaurant would have based on key features such as*

* Cuisines(The dishes served by the restaurant)
* Country
* Price range
* Average Cost for two
* Votes

*By analyzing these key features, deep insights were drawn on how they affect the eventual average rating each restaurant was given to help in maximizing input to output for these restaurants, and a predictive model was developed to help in getting the perfect services to render to give the best satisfaction to customers and invariably give a higher rating to such restaurants*


## Dataset
* Rows: 9551 entries
* Columns/Features: 21
* Target Variable: Aggregate Rating(Average Rating customers give to each restaurant after patronage).


##### Characteristics of the **Dataset** :
* Greatly Skewed Features(e.g. Average Cost For Two)
* Null Values(Target Variable)
* Need for Feature Engineering for easy interpretability and for model building


## Tools and Libraries
* Python Libraries( Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn)
* EDA


## Workflow
* **Data Collection and Data Understanding** : Loading the dataset and understanding each feature in the dataset.
* **Exploratory Data Analysis** : Analyzing the dataset and drawing correlation from the data.
* **Data Preprocessing** : Data Encoding, Data Splitting and General Preparation for Model Building
* **Model Building** : Linear Regression, Random Forest


**Insights**:
* Each Country has specific cuisines that are more popular than the other and invariably, they are more favored they are explained by countries below
![Insight](FirstInsight.jpeg)
![Insight](SecondInsight.jpeg)