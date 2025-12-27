# 🚗 Toyota Corolla Price Prediction

## 📌 Project Overview
This project builds a **prediction model for car prices** using the Toyota Corolla dataset.  
We apply **Multi Linear Regression (MLR)** and explore **feature selection** techniques to improve prediction accuracy.  
The workflow includes **Exploratory Data Analysis (EDA)**, **data preprocessing**, **model building**, and **evaluation**.

---

## 📂 Dataset Description
The dataset contains car attributes and their corresponding prices.  
We focus on the following columns:

| Column             | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| Model              | Model of the car                                                            |
| Price              | Offer Price in EUROs (Target variable)                                      |
| Age_08_04          | Age in months as of August 2004                                             |
| Mfg_Month          | Manufacturing month (1–12)                                                  |
| Mfg_Year           | Manufacturing year                                                          |
| KM                 | Accumulated kilometers on odometer                                          |
| Fuel_Type          | Fuel type (Petrol, Diesel, CNG)                                             |
| HP                 | Horsepower                                                                  |
| Met_Color          | Metallic color (Yes=1, No=0)                                                |
| Color              | Car color (Blue, Red, Grey, Silver, Black, etc.)                            |
| Automatic          | Automatic transmission (Yes=1, No=0)                                        |
| cc                 | Cylinder volume in cubic centimeters                                        |
| Doors              | Number of doors                                                             |
| Cylinders          | Number of cylinders                                                         |
| Gears              | Number of gear positions                                                    |
| Quarterly_Tax      | Quarterly road tax in EUROs                                                 |
| Weight             | Weight in kilograms                                                         |
| Mfr_Guarantee      | Manufacturer’s guarantee period (Yes=1, No=0)                               |
| BOVAG_Guarantee    | BOVAG (Dutch dealer network) guarantee (Yes=1, No=0)                        |
| Guarantee_Period   | Guarantee period in months                                                  |
| ABS                | Anti-lock braking system (Yes=1, No=0)                                      |
| Airbag_1           | Driver airbag (Yes=1, No=0)                                                 |
| Airbag_2           | Passenger airbag (Yes=1, No=0)                                              |
| Airco              | Air conditioning (Yes=1, No=0)                                              |
| Automatic_airco    | Automatic air conditioning (Yes=1, No=0)                                    |
| Boardcomputer      | Board computer (Yes=1, No=0)                                                |
| CD_Player          | CD player (Yes=1, No=0)                                                     |
| Central_Lock       | Central lock (Yes=1, No=0)                                                  |
| Powered_Windows    | Powered windows (Yes=1, No=0)                                               |
| Power_Steering     | Power steering (Yes=1, No=0)                                                |
| Radio              | Radio (Yes=1, No=0)                                                         |
| Mistlamps          | Mistlamps (Yes=1, No=0)                                                     |
| Sport_Model        | Sport model (Yes=1, No=0)                                                   |
| Backseat_Divider   | Backseat divider (Yes=1, No=0)                                              |
| Metallic_Rim       | Metallic rim (Yes=1, No=0)                                                  |
| Radio_cassette     | Radio cassette (Yes=1, No=0)                                                |
| Tow_Bar            | Tow bar (Yes=1, No=0)                                                       |

---

## 🎯 Problem Statement
Prepare a prediction model for **Price** using the given dataset:
1. Perform **EDA** to understand data distribution and relationships.
2. Apply **feature selection** to identify the most impactful predictors.
3. Build regression models and evaluate their performance.
4. Upload code to GitHub and share an **HTML Jupyter Notebook** via email.
5. Track process and timeline using **Notion.io**.

---

## 🛠️ Tech Stack
- **Python 3.9+**
- **Libraries:**
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `statsmodels`
  - `jupyter`

---

## 📑 Project Structure
