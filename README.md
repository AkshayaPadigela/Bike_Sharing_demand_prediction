# Bike_Sharing_demand_prediction

## Insights

The analysis provides insights into the patterns and relationships within bike-sharing data, helping to understand how different factors affect bike rental demand.

## Dependencies

- calendar
- numpy
- pandas
- matplotlib
- seaborn
- missingno
- datetime
- sklearn

## Notebook_Contents

1. **Data Loading and Preprocessing:**
   - Loads data from a CSV file (`bikes.csv.zip`).
   
   - Cleans and transforms data, including:
   
     - Mapping numerical values to descriptive labels.
     
     - Extracting date and weekday information.
     
     - Converting categorical variables.
     
     - Removing unnecessary columns.
     

2. **Exploratory Data Analysis:**
   - Visualizes missing values using the `missingno` library.
   
   - Creates box plots to show the distribution of bike count against various factors.
   
   - Generates a heatmap to display correlations between numerical variables.


## Steps

1. **Data Loading:** The dataset is loaded from a CSV file.
2. **Initial Processing:** The date and weekday are extracted from the 'dteday' column.
3. **Feature Identification and Data Preparation:** Categorical and numerical features are identified, and unnecessary features are dropped.
4. **Train-Test Split:** The data is split into training and testing sets.
5. **Model Training:** A Random Forest Regressor model is trained on the training set.
6. **Evaluation:** The model is evaluated using the Root Mean Squared Logarithmic Error (RMSLE) metric.
7. **Feature Importance Visualization:** The importance of each feature in the model is visualized.





## How_to_Use

1. Open the notebook in Google Colab.
2. Upload the `bikes.csv.zip` file to the Colab environment.
3. Run the notebook cells sequentially to execute the analysis.




