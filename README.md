# Facebook-Live-Engagement-Analysis

## Objective
Analyze engagement metrics in Facebook Live Seller posts using data preprocessing, correlation analysis, and unsupervised machine learning.

## Data Preparation
- Imported, cleaned, and reduced the dataset to key columns:
  - `status_id`
  - `status_type`
  - `published` (time)
  - Engagement metrics: reactions, comments, shares, likes, loves, wows, hahas, sads, angrys
- Verified that there are no missing values after dropping irrelevant columns

## Exploratory Questions & Analyses

### Effect of Publishing Time
- Explored how the time a post is published influences the number of reactions
- Analyzed temporal patterns in user engagement

### Engagement Correlations
- Analyzed correlations between reactions, comments, and shares
- Determined the strength and direction of engagement relationships
- Identified which metrics tend to move together

### Post Type Distribution
- Counted the number of posts by type (e.g., video, photo)
- Examined the composition of content types in the dataset

### Post Type Engagement Averages
- Calculated average reactions, comments, and shares for each post type
- Compared effectiveness across different content formats

## K-Means Clustering Analysis

### Model Training
- Trained a K-Means model using major engagement features
- Segmented posts into distinct engagement clusters
- Identified patterns in user interaction behavior

### Cluster Optimization
- Applied the elbow method to identify the optimal number of clusters
- Ensured meaningful and interpretable groupings of posts

## Findings
- The analysis reveals patterns in how publishing times and post types affect user engagement
- Clustering techniques help distinguish posts with similar interaction levels
- Post type summary helps identify which kinds of content drive the most engagement
- Different engagement patterns emerge based on content type and timing

## Conclusion
This project demonstrates the application of data preprocessing, exploratory data analysis, and unsupervised machine learning techniques to understand engagement patterns in Facebook Live Seller posts. The insights gained can help content creators optimize their posting strategies for maximum user engagement.
