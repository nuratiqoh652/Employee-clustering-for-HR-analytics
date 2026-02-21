# Employee-clustering-for-HR-analytics
Employee Segmentation using GMM for career growth strategy

## Project Overview
This project aims to segment employees using clustering techniques to support HR in designing personalized career development strategies.

## Business Problem
HR departments often face challenges in identifying employee groups based on performance, experience, and tenure. A data-driven segmentation approach is needed to support strategic workforce planning and career development programs.

## Methodology
- Data Cleaning & Preprocessing
- Feature Scaling
- Gaussian Mixture Model (GMM) Clustering
- Cluster Interpretation

## Key Insights
The clustering results reveal distinct employee segments with different performance and experience characteristics. These segments can support HR in designing targeted training and leadership programs.

## Project Type
This project was completed as a team collaboration.
My contribution: Data Analys & Visualitation

## Dataset
- Source: talent segmentation
- Total Rows: 1000 rows
- Total Columns: 11 columns

## Exploratory Data Analysis (EDA)
Key findings from data exploration:

- The workforce distribution across departments is relatively balanced, with no extreme dominance in a single function.
- Gender composition is fairly even (approximately 51% female and 48% male), indicating inclusive workforce representation.
- The Engineering department shows the highest average job satisfaction among all departments.
- Job satisfaction levels vary slightly by gender, but overall remain within a stable range.
- Performance and tenure distributions suggest diverse employee profiles suitable for clustering analysis.
These exploratory findings highlight the importance of segmenting employees based on performance, tenure, and satisfaction to design more targeted HR strategies

## Modeling Details
- Algorithm: Gaussian Mixture Model (GMM - Tuned)
- Number of Clusters: 3
- Feature Used: Performance Score, Tenure, Experience Level (dan fitur numerik lainnya)
- Evaluation Metrics:
  - Silhouette Score: 0.2113
  - Davies-Bouldin Index: 1.5305
  - Calinski-Harabasz Score: 281.63
- Final Model Score: 0.7391
GMM (Tuned) showed the best overall performance among tested models and produced stable and representative clusters.

## Key Insights
- Cluster 1: Most employees have participated in many training programs, but performance improvement is slow & Existing training programs no longer deliver significant impact.
- Cluster 2: High-potential employees who generate strong impact with minimal training, This cluster delivers the highest training ROI.
- Cluster 3: Early-career employees grow quickly but face higher risks of burnout and early turnover due to pressure and training overload

## Business Recommendation
- Recommendation for Cluster 1: Reduce generic training programs, Focus on targeted reskilling & job rotation, Re-evaluate training effectiveness.
- Recommendation for Cluster 2: Prioritize training investment, Implement fast-track development programs, Focus on retention & career acceleration.
- Recommendation for Cluster 3: Improve onboarding & training pacing, Provide mentoring and additional support, Focus on overall employee experience.

## Tech Stack
- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib / Seaborn
