# Customer-Segmentation
This project aims to segment customers based on their annual income and spending score using K-Means clustering.

## Dataset

The dataset used for this project is `Mall_Customers.csv`, which contains the following columns:
- `CustomerID`: Unique identifier for each customer
- `Gender`: Customer's gender
- `Age`: Customer's age
- `Annual Income (k$)`: Customer's annual income in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Methodology

1. **Data Loading and Preprocessing**
   - Loaded the dataset using Pandas.
   - Selected `Annual Income (k$)` and `Spending Score (1-100)` as features for clustering.

2. **Clustering with K-Means**
   - Implemented K-Means clustering algorithm with `n_clusters=5` to segment customers.
   - Used `n_init=10` to ensure stable cluster assignment.

3. **Visualization**
   - Visualized customer segments on a scatter plot based on `Annual Income` and `Spending Score`.
   - Each cluster is represented by a different color for clarity.

4. **Cluster Analysis**
   - Examined cluster centers to understand the characteristics of each segment.
   - Generated a customer segmentation report summarizing the number of customers, average annual income, and average spending score for each cluster.

5. **Results**
   - Saved the clustered dataset to `customer_segments.csv`.
   - Produced insights on customer segments for business strategy formulation.

## Files Included

- `Mall_Customers.csv`: Resulting dataset with assigned clusters.
- `Customer_Segmentation.ipynb`: Jupyter Notebook containing the project code.

## Dependencies

Ensure you have the following libraries installed:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Usage

1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run `Customer_Segmentation.ipynb` to reproduce the analysis and visualizations.
4. Explore `Mall_Customers.csv` for detailed customer segmentation results.

## Contributor

- Niyant Suthar
