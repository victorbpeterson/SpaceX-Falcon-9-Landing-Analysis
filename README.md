# SpaceX Falcon 9 Landing Analysis

*This is my capstone project from the IBM Data Science Professional Certificate*

## Project Overview
The commercial space age is here, and companies are attempting to make space travel affordable for everyone. Perhaps the most successful of them is SpaceX.
One reason SpaceX is leading this industry, is their rocket launches are relativily inexpensive. The Facon 9 rocket, launches with a cost of 62 million dollars; other providers cost upwards of 165 million dollars.
Much of these savings come from the fact that SpaceX can reuse the first stage of the rocket.

## Goal
To **predict whether the SpaceX Falcon 9 first stage will successfully land**. Then using this prediction, we can determine the cost of the launch, and assess whether an alternative company should bid against SpaceX.

## Project Layout
1. [Data Collection]()
   - Make GET requests to the SpaceX API
   - Perform web scraping to collect historical launch records
2. [Data Wrangling]()
   - Replace missing values with the mean
   - Determine the count of:
      - launches on each site
      - occurrence of each orbit
      - occurrence of mission outcome per orbit type
   - Create a landing outcome label that shows the following:
      - 0 when the booster did not land successfully
      - 1 when the booster did land successfully
3. [Exploratory Data Analysis]()
   - Use SQL queries to investigate and evaluate the data
   - Use Seaborn and Matplotlib to visualize relationships between attributes and apply OneHotEncoder
4. [Interactive Visual Analytics]()
   - Build a dashboard with Plotly Dash to analyze launch records interactively
   - Build an interactive map with Folium to analyze the launch site proximity
5. [Predictive Analysis (Classification)]()
   - Standardize the data
   - Split data into training and test data
   - Train different classification models
   - Find hyperparameters using GridSearchCV
   - Plot confusion matrices and determine the accuracy
   - Find the classification method that performed the best
   
