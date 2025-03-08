# Dynamic Pricing for Healthcare

## Overview
This project implements a dynamic pricing model for healthcare services, analyzing demand, capacity, and pricing trends. It consists of two main components:
1. **Jupyter Notebook (`Dynamic_Pricing_for_Healthcare.ipynb`)**: A machine learning-based dynamic pricing model.
2. **Streamlit Dashboard (`dashboard.py`)**: An interactive web dashboard to monitor and visualize healthcare pricing data.

## Features
### 1. Jupyter Notebook: Dynamic Pricing Model
- Loads and processes healthcare demand and pricing data.
- Implements a dynamic pricing algorithm based on demand and capacity fluctuations.
- Uses machine learning techniques to predict optimal pricing.
- Provides data visualization to interpret trends and pricing behavior.

### 2. Streamlit Dashboard: Healthcare Pricing Analytics
- Displays key pricing, demand, and capacity metrics.
- Provides interactive line charts and bar graphs for visualizing trends.
- Allows users to upload new data for real-time analysis.
- Enables downloading of processed data for further analysis.

## Installation
### Prerequisites
Ensure you have Python installed along with the following dependencies:
```bash
pip install streamlit pandas numpy plotly jupyter
```

## Usage
### Running the Jupyter Notebook
To run the dynamic pricing model:
```bash
jupyter notebook
```
Open `Dynamic_Pricing_for_Healthcare.ipynb` and execute the cells to analyze pricing data.

### Running the Streamlit Dashboard
To launch the interactive dashboard:
```bash
streamlit run dashboard.py
```
This will open a web-based interface displaying pricing trends and analytics.

Click here for a live demo. https://frontend-dashboard-r995dni56yb2xb5q74wpbg.streamlit.app/

## Data Input
- The dashboard loads a simulated dataset by default.
- Users can upload new CSV files to update the analysis.
- The notebook processes structured healthcare pricing datasets.

## Output
- The dashboard provides interactive visualizations and downloadable reports.
- The Jupyter notebook generates pricing insights and model predictions.

## Future Enhancements
- Integration with real-time hospital data.
- Advanced machine learning models for better price prediction.
- User authentication and role-based access control.

## Author
- Nay Linn Htin/Willie Nay


