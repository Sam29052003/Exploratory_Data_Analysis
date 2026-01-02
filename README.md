# Exploratory_Data_Analysis

# Sub Task 2.1

## Project Overview
                            This project performs Exploratory Data Analysis on a retail sales dataset to uncover patterns, relationships, and insights that influence business decisions and modeling strategies.

##  Dataset Used
                            - File: cleaned_data.csv
                            - Records include customer demographics, product categories, regions, and sales details.

##  Tools & Libraries
                            - Python
                            - Pandas
                            - NumPy
                            - Matplotlib
                            - Seaborn
                            - VS Code (Jupyter Notebook)

##  EDA Steps Performed
                            - Univariate Analysis

##  Key Insights
                            - Electronics category contributes the highest sales.
                            - Quantity and Unit Price are strong drivers of Total Sales.
                            - Sales trends vary across regions and time periods.

##  Favorite Visualization
                             - Correlation Heatmap
                             - Sales Trend Line Chart

##  Next Steps
                             - Feature engineering
                             - Encoding categorical variables
                             - Model building and evaluation



# Sub Task 2.2

# Online Food Delivery – (EDA)

##  Project Overview
                              This project performs Exploratory Data Analysis (EDA) on an Online Food Delivery Orders dataset to understand customer behavior, order patterns, and factors influencing **order                                     value.  

                              The analysis focuses on univariate, bivariate, and multivariate relationships to identify trends, correlations, and predictive signals useful for future modeling.

##  Objectives
                              - Understand the distribution of numerical and categorical variables  
                              - Analyze relationships between:
                                                    - Numerical vs Numerical
                                                    - Numerical vs Categorical
                                                    - Categorical vs Categorical
                              - Identify key factors affecting order value
                              - Discover correlations and patterns for feature selection

##  Dataset Used
                              File: `cleaned_data.csv`  
### Features Description

                             | Column Name          | Description |
                             |----------------------|------------|
                             | order_id             | Unique order identifier |
                             | city                 | City where order was placed |
                             | restaurant_type      | Type of restaurant (Fast Food, Cafe, Fine Dining, etc.) |
                             | day_of_week          | Day when the order was placed |
                             | distance_km          | Distance between restaurant and customer (km) |
                             | delivery_time_min    | Delivery time in minutes |
                             | order_value          | Total order value (INR) |

##  Tools & Libraries Used
                             - Python
                             - Pandas – Data manipulation
                             - Matplotlib – Data visualization
                             - Seaborn – Statistical plots
                             - VS Code – Development environment
                             - Jupyter Notebook

##  Analysis Performed

###  Univariate Analysis
                             - Distribution of order value
                             - Frequency of restaurant types
                             - Delivery time and distance analysis

###  Bivariate Analysis
                             - Distance vs Order Value (Scatter Plot)
                             - Restaurant Type vs Order Value (Bar Chart)
                             - City-wise average order value (GroupBy)
                             - Correlation Heatmap

###  Multivariate Analysis
                            - Pairplot for numerical variables
                            - Distance vs Delivery Time with Restaurant Type (Hue)
                            - Category-level behavioral patterns

##  Key Insights
                            - Fine Dining restaurants generate the highest average order value
                            - Order value increases with distance and delivery time
                            - Fast Food restaurants dominate the number of orders
                            - Strong correlations observed between:
                                                        - Distance and Delivery Time
                                                        - Distance and Order Value
                           - Restaurant type and city are strong predictive features

##  Favorite Visualization
                           - Correlation Heatmap – Clearly shows strong and weak relationships between numerical variables
                           - Multivariate Scatter Plot – Highlights restaurant-type-based behavior patterns

## 📁 Project Structure
