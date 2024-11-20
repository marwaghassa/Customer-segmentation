# Customer Segmentation Using Clustering Techniques

## Overview
In today's competitive market, understanding customer behavior is essential for effective marketing and maximizing profitability. This project explores customer segmentation using clustering techniques, helping businesses identify key customer groups and tailor their strategies.

## Dataset
The dataset consists of information about 2,000 customers collected through loyalty cards. Key features include:
- **Customer ID**: Unique identifier (removed for analysis)
- **Gender**
- **Marital Status**
- **Age**
- **Education**
- **Annual Income**
- **Occupation**
- **Settlement Size**

## Objective
The goal of this project is to segment customers based on their behavior using clustering techniques and provide actionable recommendations for each group.

## Methodology
### 1. Exploratory Data Analysis (EDA)
Visualized distributions for age, income, education, occupation, and settlement size. Key trends include:
- **Sex Percentage**:
  ![Sex Percentage](path/to/sex_percentage.png)
- **Marital Status**:
  ![Marital Status](path/to/marital_status.png)

### 2. Age and Income Trends
- **Scatter Plot of Income vs. Age**:
  ![Income vs Age](path/to/income_age_scatter.png)
- **Age Distribution**:
  ![Age Distribution](path/to/age_distribution.png)
- **Income Distribution**:
  ![Income Distribution](path/to/income_distribution.png)

### 3. Clustering Techniques
#### KMeans++:
- **Elbow Method**: Determined the optimal number of clusters as 4.
  ![Elbow Method](path/to/elbow_method.png)

#### Agglomerative Clustering:
- **Dendrogram**:
  ![Dendrogram](path/to/dendrogram.png)

## Key Findings
### Cluster Analysis
| Cluster | Characteristics |
|---------|------------------|
| **0**   | Single, educated males with above-average income in big cities |
| **1**   | Non-single, low-educated females with low income in small cities |
| **2**   | Highly educated males with high income in mid-size to big cities |
| **3**   | Non-single skilled individuals with below-average income in mid-sized cities |

### Cluster Centroids
| Cluster | Sex | Age | Education | Income | Occupation | Settlement Size |
|---------|-----|-----|-----------|--------|------------|-----------------|
| 0       | 0.3 | 40.9 | 1.19      | $154k  | 1.25       | 1.23            |
| 1       | 0.54| 32.2 | 0.89      | $79k   | 0.15       | 0.16            |
| 2       | 0.29| 44.6 | 1.34      | $225k  | 1.77       | 1.47            |
| 3       | 0.5 | 34.4 | 1.00      | $114k  | 0.83       | 0.71            |

## Recommendations
- **Cluster 0**: High-quality, tech-driven products; use email and social media marketing.
- **Cluster 1**: Budget-friendly products; emphasize discounts and community engagement.
- **Cluster 2**: Offer gourmet, specialty options aligned with their income level.
- **Cluster 3**: Promote affordable shopping with weekly discounts.

## Conclusion
Clustering techniques effectively segment customers into actionable groups, providing tailored strategies for marketing and profitability.

---

## How to Add the Images
To include the images:
1. Place your image files in a folder (e.g., `/images`) within your repository.
2. Replace `path/to/image.png` with the relative path to the image file.

Example:
```markdown
![Description](images/filename.png)
