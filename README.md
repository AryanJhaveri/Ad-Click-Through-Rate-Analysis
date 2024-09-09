# Cluster Analysis for Advertising Insights

## Introduction

In the fiercely competitive world of e-commerce, getting customers to click on your ads is like winning the first battle in a long campaign. It's the crucial first step in the conversion funnel, and without it, even the most impressive products go unseen. This project delves into ad click data to uncover insights and strategies for maximizing engagement, focusing on user behavior, demographics, and internet usage patterns.

## Data Overview

This project utilizes a comprehensive dataset that includes user demographics, internet usage, and ad interaction details. Key features analyzed include:
- Daily Time Spent on Site
- Age
- Area Income
- Daily Internet Usage
- Ad Click Status
  
For more details, explore the dataset on [Kaggle](https://www.kaggle.com/datasets/gabrielsantello/advertisement-click-on-ad).

## Business Questions Addressed

This project tackled several critical business questions to drive strategic advertising decisions:

1. **What demographic factors most influence ad click-through rates?**
   - By analyzing user demographics such as age and income, the project identified key segments that are more likely to engage with ads. This insight allows for more targeted marketing strategies.

2. **How does internet usage correlate with ad engagement?**
   - The analysis revealed patterns in daily internet usage and their impact on ad clicks, helping to optimize ad placement and content for different user activity levels.

3. **When are users most likely to click on ads?**
   - Temporal analysis uncovered peak times for ad engagement, providing data-driven recommendations for scheduling ad campaigns to maximize visibility and interaction.

4. **What are the characteristics of user segments with high ad engagement?**
   - Through cluster analysis, distinct user groups were identified, each with unique behaviors and preferences. This segmentation supports tailored advertising approaches to enhance engagement and conversion rates.

Each of these questions was addressed through rigorous data analysis, providing actionable insights to improve advertising strategies and outcomes.

## Key Findings

### Impact of Daily Time Spent on Site and Area Income
<table>
  <tr>
    <td>
      <strong>Daily Time Spent on Site</strong>: Users who clicked on ads spent less time on the site on average compared to those who did not click. This suggests that ads are effectively capturing the attention of users with specific needs or interests early in their visit.
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/80c184a3-462e-4b1c-9a7e-2774b8372ffb" alt="Density Plot of Daily Time Spent on Site" width="1700"/>
    </td>
  </tr>

  <tr>
    <td>
      <strong>Area Income</strong>: Users with lower area income were more likely to click on ads. This indicates that ads might be targeted towards users looking for economical options.
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/c7c93ab1-0983-4d59-96ab-a24ae59d38b6" alt="Density Plot of Daily Time Spent on Site" width="1700"/>
    </td>
  </tr>
</table>


### Cluster Analysis

<table>
  <tr>
    <td>
      Through cluster analysis, three distinct user segments were identified, providing insights for tailored advertising strategies:
      <ul>
        <li><strong>Cluster 1</strong>: High internet usage but low ad-click rates. This group might require more engaging or relevant ad content to increase interaction.</li>
        <li><strong>Cluster 2</strong>: Moderate internet usage with very high ad-click rates. This segment represents high potential value for targeted campaigns.</li>
        <li><strong>Cluster 0</strong>: Similar to Cluster 1 in behavior but with the lowest area income, suggesting sensitivity to economic factors and a preference for affordable products.</li>
      </ul>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/7ddd3e71-25ff-49a4-819d-8532282ab07d" alt="Cluster Summary" width="1500" hight="2500"/>
    </td>
  </tr>
</table>

For a more in-depth analysis of each cluster, including temporal analysis and additional insights, please refer to the complete analysis in the [Jupyter Notebook](cluster-analysis-for-advertising-insights.ipynb).

## Implications and Recommendations

- **Tailored Content**: Craft ads that resonate with the preferences and habits of each user cluster.
- **Strategic Timing**: Align ad campaigns with peak times identified through timestamp analysis to maximize reach.
- **Economic Targeting**: Factor in the economic backgrounds of clusters to inform product selection and ad messaging.

## Technology Stack

- Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Machine Learning: Scikit-learn for clustering

## Getting Started

Interested in the detailed analysis? Get started here:

```bash
git clone https://github.com/your-username/cluster-analysis-advertising.git
cd cluster-analysis-advertising
jupyter notebook cluster-analysis-for-advertising-insights.ipynb
