# brazilian-commerce-repeat-buyers
This is for predicting which first-time buyers in a Brazilian e-commerce dataset will make a repeat purchase within 120 days.


# Predicting Repeat Purchase Behavior of First-Time Buyers (Olist)

Data Science course project — E-Commerce & Customer Intelligence track.

## Problem
Predict which first-time buyers in the Olist Brazilian e-commerce dataset
will make a repeat purchase within 120 days.

## Dataset
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- ~100,000 orders, 2016–2018
- 9 relational tables (customers, orders, items, payments, reviews, products, sellers, geolocation, category translation)

Download the CSVs and place them in `data/raw/`.

## Team
- Mason Driggers
- Alyssa Ortiz
- Sebastian Ramirez
- Angela Monroy

## Setup
```bash
git clone <repo-url>
cd olist-repeat-purchase-prediction
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
