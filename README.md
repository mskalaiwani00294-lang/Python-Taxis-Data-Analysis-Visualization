#🚕 Taxis Data Analysis & Visualization

##📌 Overview

-This project analyzes the Taxis dataset using Python, Pandas, Matplotlib, and Seaborn. The project focuses on data cleaning, handling missing values, exploratory data analysis, and creating different visualizations to understand taxi trip patterns, fares, distances, tips, payment methods, and pickup locations.

###🎯 Objective

-The objective of this project is to clean and analyze taxi trip data and use different visualizations to identify patterns, distributions, and relationships between important variables such as fare, distance, tip, total, payment method, and pickup borough.

🛠️ Tools & Technologies

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 📈 Seaborn
- 📓 Jupyter Notebook / Google Colab

##📂 Dataset

-The project uses the Seaborn Taxis dataset.

-Important columns include:

- "pickup" – Pickup timestamp
- "dropoff" – Drop-off timestamp
- "passengers" – Number of passengers
- "distance" – Trip distance
- "fare" – Taxi fare
- "tip" – Tip amount
- "tolls" – Toll amount
- "total" – Total trip amount
- "payment" – Payment method
- "pickup_borough" – Pickup borough
- "pickup_zone" – Pickup zone
- "dropoff_borough" – Drop-off borough
- "dropoff_zone" – Drop-off zone

##🧹 Data Cleaning

-The following data-cleaning steps were performed:

- Checked for missing values.
- Identified columns containing missing data.
- Filled numerical missing values using the median.
- Filled categorical missing values using the mode.
- Removed rows with missing values from critical columns where necessary.
- Converted the "pickup" column to datetime format.

##📊 Visualization & Analysis

-1. 📈 Time & Trend Analysis

-Line Chart – Fare Over Time

-Used to understand how taxi fares change according to pickup time.

-2. 📍 Categorical Analysis

-Bar Chart – Total Fare by Pickup Borough

-Used to compare total fare across pickup boroughs.

-Pie Chart – Payment Method Distribution

-Used to understand the distribution of trips by payment method.

-Count Plot – Trips by Pickup Borough

-Used to compare the number of taxi trips across boroughs.

##3. 📊 Distribution Analysis

-Histogram – Distance

-Used to understand the distribution of taxi trip distances.

-Box Plot – Tip by Pickup Borough

-Used to compare tip distributions and identify possible outliers.

-Violin Plot – Fare by Payment Method

-Used to understand fare distribution across different payment methods.

##4. 🔗 Relationship & Correlation Analysis

-Scatter Plot – Distance vs Fare

-Used to examine the relationship between trip distance and fare.

-Heatmap – Correlation Analysis

-Used to analyze relationships between "distance", "fare", "tip", "tolls", and "total".

##Pair Plot

-Used to compare pairwise relationships between "distance", "fare", "tip", and "total" across pickup zones.

##🔍 Key Insights

- Taxi fares vary across different trips and pickup locations.
- Trip distance provides useful information for analyzing fare patterns.
- Payment methods show different levels of usage among trips.
- Tip amounts vary across pickup boroughs.
- The scatter plot helps examine the relationship between distance and fare.
- The heatmap highlights correlations among important numerical variables.
- Different visualizations provide a broader understanding of taxi trip behavior.

##💡 Interpretation

-The visualizations provide a clear understanding of taxi trip patterns, fare trends, distance, tips, payment methods, and pickup locations. The combination of categorical, distribution, time-based, and relationship analysis helps identify important patterns within the dataset.

##📌 Conclusion

-The Taxis dataset was successfully cleaned and analyzed using Python, Pandas, Matplotlib, and Seaborn. Multiple visualizations were created to explore taxi fares, distances, tips, payment methods, and pickup locations. Overall, the project demonstrates practical skills in data cleaning, exploratory data analysis, data visualization, and interpreting business-related insights.

👩‍💻 Author

M. Kalaivani
Aspiring Data Analyst

⭐ Skills Demonstrated

"Python" "Pandas" "NumPy" "Matplotlib" "Seaborn" "Data Cleaning" "EDA" "Data Visualization"
