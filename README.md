# AI-COMPARATIVE_PRICE_ANALYSIS_INTERIOR_DESIGN

1. AI project for market trend analysis in Interior Design

#Interior design costs change significantly over time. This project applies AI driven time series forecasting to analyze pricing patterns from old dataset and predict future trends using Prophet.

#Objectives:
- Compare historical pricing trends across categories
- Compute growth and volatility
- Forecasting prices for the next 12 months
- Provide insights for Budgets and planning

#Dataset:
- Simulated dataset (Jan 2022- Dec 2024)
- Columns: Columns: 'Date', 'Category', 'Price'
- Categories: Furniture, Lighting, Flooring, Decor

#Methodology:
1. Data preprocessing
2. Exploratory Data Analysis (comparative line plots)
3. Growth & Volatility analysis (CAGR, monthly returns)
4. Forecasting with Prophet
5. Visualization of results

#Tools & Libraries:
- Python, Google Colab
- pandas, matplotlib, seaborn
- prophet

#Results:
- Furniture: Steady growth
- Lighting: Faster growth
- Flooring: Most stable, low volatility
- Decor: Sharpest rise, high volatility

2.Open AI_for_Comprative_price_analysis_in_Interior_design.ipynb in Google Colab or Jupyter Notebook.

2.Upload interior_design_prices.csv in the same runtime folder.

3.Run all cells top-to-bottom

4.Project structure
├── AI_for_Comprative_price_analysis_in_Interior_design.ipynb       # main code

├── interior_design_prices.csv          # dataset

├── all_category_forecast_next12m.csv   # forecast output (generated)

├── README.md                           # documentation

5.Future scope:
- Use of real world datasets
- Build dashboard
