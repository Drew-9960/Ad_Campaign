# A/B Testing for AD Campaign

## Project Overview

This project focuses on analyzing an A/B test designed to evaluate the effectiveness of a marketing campaign. The primary objective is to determine whether the campaign was successful and quantify how much of the success can be attributed to the ads.

## Key Questions

1. **Would the campaign be successful?**
2. **If the campaign was successful, how much of that success could be attributed to the ads?**

## Methodology

To answer these questions, an A/B test was conducted with the following groups:

- **Experimental Group**: Majority of participants exposed to the ads.
- **Control Group**: Smaller portion of participants shown a Public Service Announcement (PSA) or nothing at all, in the exact size and placement as the ad.

The analysis includes:

1. **Data Cleaning and Preparation**: Ensuring the dataset is ready for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding the distribution of variables, relationships, and any potential anomalies.
3. **Hypothesis Testing**: Evaluating whether the observed differences between the experimental and control groups are statistically significant.
4. **Effect Size Calculation**: Quantifying the success attributable to the ads.
5. **Conclusion**: Summarizing findings and providing actionable insights.

## Data Dictionary

- **Index**: Row index.
- **User ID**: Unique identifier for each user.
- **Test Group**: Indicates whether the user saw the advertisement (`"ad"`) or the public service announcement (`"psa"`).
- **Converted**: Boolean indicating if the user purchased the product (`True` for purchase, `False` for no purchase).
- **Total Ads**: The total number of ads seen by the user.
- **Most Ads Day**: The day on which the user saw the highest number of ads.
- **Most Ads Hour**: The hour of the day when the user saw the highest number of ads.

## Analysis Process

The project follows a structured and fully commented process:

1. **Data Cleaning**: Handling missing values and duplicates.
2. **EDA**: Visualizing and summarizing the data.
3. **Hypothesis Testing**: Performing t-tests, Mann-Whitney U tests, and chi-square tests to determine the significance of differences between groups.
4. **Effect Size and Lift Calculation**: Estimating the improvement in conversion rates and potential revenue gain.
5. **Conclusion**: Providing insights and recommendations based on the analysis.

## Results

- The campaign was successful, with the ad group showing a statistically significant higher conversion rate compared to the PSA group.
- The lift calculation indicated a 43% increase in conversions due to the ads.
- The potential revenue gain from the ads was estimated at $700,150, based on an average revenue per conversion of $50.

## Conclusion

This analysis provides strong evidence that the marketing campaign's success can be largely attributed to the advertisements. The detailed statistical testing supports the effectiveness of the ads in driving conversions, offering valuable insights for future marketing strategies.
