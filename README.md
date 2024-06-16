# 8  General Conclusion for the Real Estate Data Analysis

## 8.1  Key Steps and Findings:

### 8.1.1  Data Cleaning:
- We started by combining the latest ITBI transactions with previous years' data to create a comprehensive time series dataset.

- Missing values and inconsistent entries were addressed, ensuring data quality and reliability.

### 8.1.2  Outlier Identification and Handling:

- Significant outliers in the dataset were identified, particularly in the price per square meter (ppsqm) and sale price columns.

- We established thresholds to filter out extreme values: prices per square meter between 1,500 and 150,000 BRL, and sale prices between 150,000 and 15,000,000 BRL.

- Property size filters were applied: for apartments/flats, sizes between 19 and 1,000 square meters; for houses (Casas), sizes between 70 and 10,000 square meters.

### 8.1.3  Price Per Square Meter Analysis:

- After applying the filters, we analyzed the price per square meter, revealing a general positive correlation between construction year and price, as expected.

- The majority of properties were priced below 20,000 BRL per square meter, with notable outliers in certain categories and years that warranted further investigation.

### 8.1.4  Category-Specific Insights:
- Houses (Casas) constructed in the 1960s-1970s showed a high number of outliers, possibly due to historical value or data inconsistencies.

- Apartments constructed in the 2020s had significant outliers, likely reflecting new developments in prime locations or luxury properties.

### 8.1.5  Data Preparation for Visualization:
- The cleaned and filtered dataset was prepared for visualization, with particular attention to creating a file suitable for integration into a Power BI dashboard. A linkage with the pre-generated shapefile of Sao Paulo neighborhoods was established to provide geographical context for the analysis.

### 8.1.6  Next Steps:
- Further Analysis: Continue exploring the dataset to identify trends and patterns, particularly focusing on the identified outliers to understand their causes and implications.
- Visualization: Develop comprehensive visualizations using the cleaned dataset to provide clear insights into the real estate market trends in Sao Paulo.
- Integration: Integrate the prepared dataset into the Power BI dashboard to enable dynamic and interactive data exploration for stakeholders.

## Conclusion: 

This analysis has laid a solid foundation for understanding the real estate market in Sao Paulo. By meticulously cleaning the data and handling outliers, we have ensured that the dataset is reliable and ready for in-depth analysis and visualization. These efforts will significantly contribute to informed decision-making and strategic planning in the real estate sector.
