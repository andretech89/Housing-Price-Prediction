# House Price Prediction

This project uses machine learning to predict house prices based on housing, economic, and geographic features. Built using Python, pandas, scikit-learn, and visualized with matplotlib and seaborn.


## Features

- Uses real-world housing data from HouseTS.csv
- Predicts house prices using linear regression
- Compares monthly average prices between 2012 and 2023
- Visualizes feature importance and price trends


## Project Structure

- house-price-prediction/
   - house\_price\_predictor.ipynb  # Main notebook with code and visualizations
   - HouseTS.csv                  # Dataset
   - requirements.txt             # Dependencies
   - README.md                    # Project description
   - .gitignore                   # Git exclusions



## Example Visualization

Average house price by month in 2012 vs 2023:

![Monthly Average Price](price_trend_2023_vs_2012.png)

> *(This image will only display if you saved and committed the plot as an image file using plt.savefig(...))*


## How to Run

1. Clone the repo:
   
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction


2. Set up a virtual environment (optional but recommended):
   
   python -m venv venv
   venv\Scripts\activate  # On Windows
   

3. Install dependencies:
   
   pip install -r requirements.txt
   

4. Launch Jupyter Notebook:
   
   jupyter notebook
   



