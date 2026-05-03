 📊 Dataset
- File customer_segmentation_data.csv
- Features
  - minutes_watched: Total engagement time on platform
  - CLV: Customer Lifetime Value (monetary measure)
  - region: Encoded region/country
  - channel: Acquisition channel (e.g., Twitter, Facebook, LinkedIn, Friends)

---

  Methodology
1. Data Loading & Cleaning
   - Handle missing values
   - Normalize/scale numerical features
   - Encode categorical variables
2. Exploratory Data Analysis (EDA)
   - Distribution plots
   - Correlation heatmaps
   - Scatter plots (Minutes Watched vs CLV)
3. Clustering
   - K-means clustering (Elbow Method for optimal k)
   - Hierarchical clustering (Ward’s method, dendrogram)
    Insights
   - Identify high-value segments
   - Compare engagement by acquisition channel
   - Recommend marketing strategies

---

 Expected Outcomes
- Segmentation of customers into meaningful clusters
- Identification of acquisition channels that bring **high CLV customers**
- Actionable recommendations for marketing investment



 Tech Stack
- Python
- pandas
- scikit-learn
- seaborn
- matplotlib
- Jupyter Notebook

