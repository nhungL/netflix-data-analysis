## Netflix Movies and TV Shows Data Analysis
Data visualization project of Covid-19 virus for the continental US.

Source: https://www.kaggle.com/shivamb/netflix-shows

## Technologies and Implementations
The project is created with:
* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn

## Data Processing (Pandas DataFrame)
* Merge raw cases and deaths data into one dataframe
* Remove unnecessary information such as uid, lat, long, cruise ships and non-continental US region 
* Transform from wide to long dataframe by pivoting the date columns to rows
* Perform calculation to transform the dataset from counties to states and the US
* Perform calculation to add daily cases and daily deaths data
* Replace missing value NaN with 0
* Create a second dataframe that includes data for the US overall

## Graphs and Plots
* US total cases and deaths
* US fatality rate
* US total daily cases
* US choropleth map
* US daily Cases heatmap
* Total cases of states
* Daily cases of states
* Top 5 with the most cases
* Top 5 fatality rate vs US fatality rate
* Top 5 daily cases & US average daily cases
* Timeline comparison of top 5 states
