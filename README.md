# Customer Segmentation using K-Means Clustering

## Overview
This project applies K-Means clustering to segment customers based on their annual income and spending score. The dataset is analyzed, preprocessed, and visualized to identify distinct customer groups.

## Dataset
- **Source**: `Mall_Customers.csv`
- **Columns**:
  - `CustomerID` - Unique ID for customers
  - `Gender` - Customer gender
  - `Age` - Customer age
  - `Annual Income (k$)` - Annual income in thousands
  - `Spending Score (1-100)` - Customer's spending behavior

## Steps Performed
1. **Data Collection & Exploration**
   - Loaded dataset using Pandas
   - Checked for missing values and dataset structure  
2. **Feature Selection**
   - Selected `Annual Income` and `Spending Score` as clustering features  
3. **Choosing Optimal Clusters**
   - Used the **Elbow Method** to determine the optimal number of clusters (WCSS plot)  
4. **Training K-Means Model**
   - Trained a K-Means model with `n_clusters=5`  
5. **Visualization**
   - Plotted customer clusters with centroids  

## Technologies Used
- Python (NumPy, Pandas, Matplotlib, Seaborn)
- Scikit-learn (K-Means Clustering)

## Results
- Successfully segmented customers into **five groups** based on income and spending habits.
- Generated insights for targeted marketing strategies.

## How to Run
1. Install dependencies:  
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn

   python customer_segmentation.py


