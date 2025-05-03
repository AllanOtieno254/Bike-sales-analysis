# Bike Sales Data Analysis

![database](https://github.com/user-attachments/assets/9b3d35a8-051c-44e1-99ac-3c98d50d3dc6)

## Overview
This project conducts in-depth analysis and visualization on a bike sales dataset, identifying key insights such as customer revenue distribution, age group purchasing trends, profit margins by region, and inter-feature correlations.
![subplotsbox](https://github.com/user-attachments/assets/c51fc85c-b36d-419c-8f0c-2e8aea805aee)
![corr](https://github.com/user-attachments/assets/6d904666-9de6-401c-8354-2f1e6f133874)

## Key Questions Answered
- What is the distribution of unit cost and profit?
- How does revenue vary across age groups?
- What age group is the most profitable?
- What are the relationships (correlations) between numerical features?
- Which countries have the highest revenue?
- What are the buying behaviors across different age categories?
![box1](https://github.com/user-attachments/assets/db6ef509-f688-4e57-a408-8544b083d98d)
![bar](https://github.com/user-attachments/assets/e1e67c0b-61fb-47ed-bce1-797029ec466f)
![pie](https://github.com/user-attachments/assets/c2d96bc7-1813-4f96-be6c-ba95bd1928e7)
![density](https://github.com/user-attachments/assets/107fbc3d-958b-4bec-92bb-2b07fc1be850)

## Tools Used
- **Pandas** for data manipulation
- **Matplotlib** and **Seaborn** for visualizations
- **NumPy** for numerical operations
- **Google Colab** for notebook development

## Features Visualized
- Density plots of `Unit_Cost`
- Box plots for `Profit` across age groups
- Heatmaps for correlation matrix
- Scatter plots of `Customer_Age` vs. `Revenue`
- Group-wise mean calculations (age + country)

## Notable Insights
- Adult (35-64) customers generate the highest revenue.
- France's revenue increased by 10% using simulation.
- Highest correlation exists between `Unit_Cost` and `Unit_Price`.
- Outliers exist in `Order_Quantity`, and `Profit`.

## File Structure
- `notebooks/`: Jupyter notebooks
- `data/`: Raw or cleaned datasets
- `images/`: Visuals used in README or reports
- `outputs/`: Text summaries or final reports

## How to Run
1. Clone the repository
2. Install dependencies via `pip install -r requirements.txt`
3. Launch the notebook using `jupyter notebook`
4. Open `Bike_sales_analysis.ipynb`

## Example Visualizations
- Correlation Matrix Heatmap
- Boxplot for Profit per Age Group
- Revenue Distribution per Country

## Future Work
- Apply machine learning for sales prediction
- Deploy dashboard using Streamlit
- Analyze seasonal trends

## Author
[Your Name] - Data Analyst & Python Enthusiast
