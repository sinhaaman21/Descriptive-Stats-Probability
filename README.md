# AeroFit Case Study: Data Analysis and Customer Profiling

This project analyzes the AeroFit treadmill dataset to uncover insights about customer purchasing behavior. The analysis includes data preprocessing, exploratory data analysis (EDA), outlier detection, correlation analysis, and customer profiling using clustering techniques.

## Project Overview

### Objectives

1. **Data Import and Initial Analysis**:
   - Load and explore the dataset to understand its structure and characteristics.

2. **Outlier Detection**:
   - Identify outliers using visualizations and statistical methods.

3. **Feature Effect Analysis**:
   - Investigate the impact of features like marital status and age on product purchases.

4. **Marginal Probabilities**:
   - Calculate and interpret the marginal probabilities for different treadmill products.

5. **Correlation Analysis**:
   - Examine the relationships between various features using heatmaps and pair plots.

6. **Customer Profiling**:
   - Segment customers using clustering techniques for targeted marketing strategies.

### Dataset

The dataset includes information about customers who purchased treadmills, with the following features:
- Product: Type of treadmill purchased (KP281, KP481, KP781)
- Age: Age of the customer
- Gender: Gender of the customer
- Education: Years of education
- MaritalStatus: Marital status of the customer
- Usage: Average usage of the treadmill per week
- Fitness: Self-rated fitness level (1-5)
- Income: Annual income of the customer
- Miles: Expected miles to walk/run on the treadmill per week

## Steps and Analysis

### 1. Importing and Analyzing the Dataset

- **Import the dataset** and display its structure using `info()` and `describe()` methods.
- **Check for missing values** and ensure data completeness.

### 2. Outlier Detection

- **Visualize distributions** using histograms for features like Age, Education, Usage, Fitness, Income, and Miles.
- **Identify outliers** using box plots and the difference between the mean and median.

### 3. Feature Effect Analysis

- **Explore the distribution** of qualitative attributes such as Product, Gender, and Marital Status using count plots.
- **Analyze the relationship** between features like Marital Status, Age, and Product purchase using count plots, histograms, and box plots.

### 4. Marginal Probabilities

- **Calculate marginal probabilities** for each treadmill product using pandas crosstab.

### 5. Correlation Analysis

- **Generate a correlation heatmap** to visualize the relationships between numerical features.
- **Create pair plots** to examine pairwise relationships and distributions.

### 6. Customer Profiling

- **Normalize features** and perform K-means clustering to segment customers.
- **Visualize clusters** based on Age and Income.
- **Analyze segment details** to understand customer profiles.

## Insights and Recommendations

### Insights

- **Product Preferences**: KP281 is the most sold product, and partnered customers show a higher purchase rate.
- **Gender and Marital Status**: KP481 has a slightly higher preference among male customers, while partnered customers prefer KP781.
- **Customer Segmentation**: Three customer segments were identified based on Age, Education, Usage, Fitness, Income, and Miles.

### Recommendations

1. **Targeted Marketing**:
   - Create gender-neutral campaigns for KP281 and KP781.
   - Highlight features appealing to male customers for KP481.

2. **Product Development**:
   - Develop advanced models for fitness-conscious Segment 2 customers.

3. **Pricing Strategy**:
   - Offer premium features for KP781 targeting higher income customers.

4. **Customer Experience**:
   - Offer family-oriented promotions for Segment 0.

5. **Retention Strategies**:
   - Implement loyalty programs for repeat customers.

6. **Cross-Selling Opportunities**:
   - Recommend complementary products based on initial purchases.

7. **Feedback Collection**:
   - Collect customer feedback to improve products and services.

8. **Segment-Specific Campaigns**:
   - Tailor campaigns to each segment’s preferences.

9. **Product Differentiation**:
   - Highlight unique features of each product in marketing materials.

## Repository Structure

- `AeroFit_CaseStudy_Scaler.ipynb`: Jupyter notebook containing the complete analysis and customer profiling.
- `aerofit_treadmill.csv`: Dataset used for the analysis.

## Usage

To run the analysis, follow these steps:

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```
3. Open the Jupyter notebook:
    ```bash
    jupyter notebook AeroFit_CaseStudy_Scaler.ipynb
    ```
4. Run the cells in the notebook to execute the analysis.

## Conclusion

This project provides a comprehensive analysis of the AeroFit treadmill dataset, revealing key insights into customer behavior and offering actionable recommendations to improve marketing strategies and product offerings.
