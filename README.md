# SaaS Customer Segmentation and Discount Analysis

**Description**

A data-driven project focused on segmenting SaaS customers using data aggregation and analyzing discount strategies to optimize sales and profit. Includes detailed EDA, customer segmentation, and actionable insights to improve marketing campaigns and customer retention.

## Project Overview

This project focuses on segmenting customers of a SaaS (Software as a Service) company and analyzing discount strategies. The goal is to understand customer behavior, group similar customers together using data aggregation techniques, and analyze how discounts impact sales and profit. By leveraging customer segmentation, we aim to create more targeted marketing strategies and improve business performance.

## Objectives

- Segment customers based on usage patterns and demographic data.
- Identify key segments for targeted marketing campaigns.
- Analyze the impact of discounts on different customer segments.

## Dataset

The dataset used in this project was sourced from Kaggle and contains information about SaaS customer activities, demographics, and their response to discounts. It includes features such as customer ID, usage frequency, subscription plan, and discount offered.

## Methodology

1. **Data Preprocessing**: Cleaned the data by handling missing values, normalizing numerical features, and encoding categorical features.
2. **Customer Segmentation**: Used data aggregation techniques to group customers into distinct segments based on behavioral data.
3. **Discount Analysis**: Performed exploratory data analysis (EDA) to assess the effect of discount offers on sales and profit performance.
4. **Insights & Recommendations**: Developed actionable insights for marketing strategies.

## Key Insights

Customers could be grouped into 3 main segments based on their activity and plan type:

- **Segment High Sales**: Customers in this segment have generated the highest sales, falling above the 75th percentile of total sales. These customers are highly valuable, and discount strategies should focus on retaining their loyalty without significantly reducing profit.
- **Segment Medium Sales**: Customers in this segment have sales between the 25th and 75th percentiles. They are responsive to targeted discount strategies, which can help increase both sales and retention.
- **Segment Low Sales**: Customers in this segment fall below the 25th percentile of total sales. Discounts should be used strategically to encourage repeat purchases while minimizing profit loss.
- The ideal discount interval where sales remain high, but profit is not negative, is between 0.5 and 0.6. The safest discount rate is 50% to avoid significant profit reduction.
- Discounts should be personalized based on customer segments, with a focus on maximizing engagement from **Segment B** and **Segment C** through strategies like tiered discounts and bundling.

## Tools Used

- **Python**: For data analysis and visualization.

- **Pandas & NumPy**: For data cleaning and manipulation.

- **Matplotlib & Seaborn**: For data visualization.

## How to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/ffarishelmi/SaaS-Customer-Segmentation-and-Discount-Analysis.git
   ```
2. Install the additional dependencies:
   ```sh
   pip install plotly
   ```
3. Run saas\_customer\_segmentation.ipynb file the notebook environment you are using.

## Conclusion

This project demonstrates how customer segmentation can be effectively used to personalize discount strategies and boost customer retention in a SaaS environment. The results highlight the importance of understanding different customer segments and their unique needs.

## Next Steps

- Implementing a recommendation engine to suggest subscription upgrades.
- Testing different discount offers on specific customer segments in A/B tests.

Feel free to contribute by suggesting improvements or adding new features!
