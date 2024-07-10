# Electric Vehicle Analysis Project

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Installation](#installation)
- [Usage](#usage)
- [Key Insights](#key-insights)
- [Contributors](#contributors)
- [License](#license)

## Project Overview
This project focuses on the data analysis of electric vehicles to understand various factors influencing their market, pricing, and efficiency. The analysis includes exploratory data analysis (EDA), correlation analysis, and deriving actionable insights for market positioning and operational efficiency.

## Data Sources
The data for this project was collected from the following sources:
- [Kaggle: Electric Cars EDA with Feature Engineering](https://www.kaggle.com/code/vencerlanz09/electric-cars-eda-with-feature-engineering)
- [Kaggle: Soviets World Trade - Past and Present](https://www.kaggle.com/code/pranav941/soviets-world-trade-past-and-present/input)
- [GitHub: Electric Vehicle Market Segmentation](https://github.com/BairagiSaurabh/Electric-Vehicle-Market-Segmentation)
- [Data.gov.in: State/UT-wise Number of Anganwadi Workers](https://community.data.gov.in/state-ut-wise-number-of-anganwadi-workers-as-on-31-12-2023/)
- [YouTube: Exploratory Data Analysis](https://www.youtube.com/watch?v=V1kBtbvTef8)

## Installation
To run this project, you need to have Python installed on your system along with the following libraries:
- pandas
- matplotlib
- seaborn
- numpy
- pygwalker (if applicable)

You can install the required libraries using:
```bash
pip install pandas matplotlib seaborn numpy pygwalker
```

## Key Insights
- Range and Price Correlation: Higher vehicle range tends to correlate with higher prices.
- Efficiency and Price Correlation: More efficient vehicles (lower Wh/km) generally have higher prices.
- Plug Type Analysis: Type 2 plug types are common in the highest range and costliest vehicles.
- Top Selling Brands: Tesla, Porsche, Skoda, Nissan, Audi, and Volkswagen lead the market.
- Popular Car Types: SUVs dominate the electric vehicle market.
- Segment Analysis: S segment cars (sports cars) are the most expensive.

## Features Considered
The following features were analyzed in this project:

- Brand: The manufacturer of the vehicle.
- TopSpeed_KmH: The top speed of the vehicle in kilometers per hour.
- FastCharge_KmH: The range added per hour of fast charging.
- PowerTrain: The type of powertrain the vehicle uses.
- PlugType: The type of plug the vehicle uses for charging.
- BodyStyle: The body style of the vehicle (e.g., SUV, sedan).
- Segment: The market segment the vehicle belongs to (e.g., S segment).
- Seats: The number of seats in the vehicle.
- PriceEuro: The price of the vehicle in euros.
- Range_km_binned: The binned range of the vehicle in kilometers.
- efficiency_WhKm_binned: The binned efficiency of the vehicle in watt-hours per kilometer.


## Interactive Dashboard
- The repository includes an Excel file with the dataset, which was used to build an interactive dashboard. The dashboard provides a user-friendly interface for exploring the data and gaining insights.
