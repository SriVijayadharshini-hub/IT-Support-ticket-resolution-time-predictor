# IT Support Ticket Resolution Time Predictor

## Project Overview
This project predicts the resolution time of IT support tickets in a mid-size tech company. It uses regression models to estimate the number of hours required to resolve tickets and clustering to group tickets by type, priority, and department. The project also provides an interactive dashboard for visual analysis.

## Features
1. **Regression Models**
   - Predicts ticket resolution time based on features:
     - Ticket Type
     - Priority
     - Department
     - Reported Hours
   - Models used:
     - Linear Regression
     - Random Forest Regression

2. **Clustering**
   - Groups tickets into clusters using **KMeans** and **PCA**.
   - Helps identify patterns and similarities between tickets.

3. **Dashboard Reporting**
   - Interactive visualizations using **Plotly**:
     - Scatter plot: Ticket Type vs Resolution Time (by cluster)
     - Box plot: Resolution Time by Priority
     - Bar chart: Average Resolution Time by Department

4. **CSV Export**
   - Saves predictions for further analysis.

---

## Technologies Used
- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn (Regression, Clustering, PCA)
- Matplotlib & Seaborn (Plots)
- Plotly (Interactive Dashboard)

### Prerequisites
Install required Python packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly
