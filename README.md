# Shipment-Delay-Analysis-and-Prediction

This project analyzes and predicts shipment delays using machine learning techniques. It includes data manipulation, feature engineering, model training, and visualization to provide actionable insights for operational teams and stakeholders.

## Project Overview

Operational efficiency and timely deliveries are crucial for logistics and shipping companies. This project aims to analyze shipment data, predict potential delays, and provide recommendations to improve carrier performance.

## Key Features

1. **Data Preparation and Exploration:**
   - Load and inspect datasets (`GPS_data.csv`, `Shipment_bookings.csv`, `New_bookings.csv`).
   - Merge datasets to create a comprehensive view of shipment data.

2. **Analysis and Modeling:**
   - Analyze on-time delivery performance within a specified date range.
   - Use logistic regression to identify shippers at risk of delays.
   - Train a RandomForestClassifier to predict delays for new bookings.

3. **Visualization:**
   - Visualize the frequency and average delay of different vehicle sizes and build types.
   - Generate plots to summarize analysis findings and communicate insights effectively.

4. **Prediction and Notification:**
   - Predict the likelihood of delays for new shipments.
   - Identify shippers who should be notified of potential delays.

## Repository Structure

- `data/`: Contains the dataset files used in the project.
- `notebooks/`: Jupyter notebooks for data analysis, modeling, and visualization.
- `src/`: Python scripts for data processing, feature engineering, and model training.
- `visualizations/`: Plotly visualizations and graphs.
- `README.md`: Project overview and instructions.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Shipment-Delay-Analysis-and-Prediction.git
