**Retail Demand Intelligence**

**Overview**

Retail Demand Intelligence is a data science project focused on analysing and forecasting retail demand using transactional and inventory data. The project demonstrates how raw retail data can be transformed into actionable demand insights suitable for real-world decision-making.

**Objectives**

* Define a robust demand metric from retail data

* Create a clean daily demand time series

* Analyse key demand drivers (pricing, promotions, category, region)

* Build a model-ready dataset for forecasting

* Establish a defensible baseline forecast

**Dataset Highlights**

* Units Sold (demand target)

* Pricing, discounts, and competitor pricing

* Promotions and contextual features

* Product category and regional attributes

**Approach**

* Cleaned and validated raw retail data (including real-world schema issues)

* Aggregated store- and product-level data to daily demand

* Performed exploratory analysis of temporal and categorical drivers

* Engineered time-based and pricing features

* Built and evaluated a baseline forecast using MAE


## Project Structure
```
Retail-Demand-Intelligence/
│
├── data/
│   ├── raw/            # Original retail dataset
│   └── processed/      # Cleaned and aggregated data
│
├── notebooks/
│   └── 01_data_exploration.ipynb
│
├── .venv/              # Virtual environment (ignored)
├── README.md
└── .gitignore
```

**Tools**

Python (pandas, numpy), Matplotlib, Seaborn, scikit-learn, Jupyter Notebook, Git/GitHub, VSC

**Next Steps**

- Advanced forecasting models 

- Feature encoding for machine learning

- Model comparison and performance evaluation
