## Project Overview

In Colombia, shopping malls play an important role in the retail industry. In one place, customers can buy groceries, clothes, books, toys, jewelry, home appliances, and even access banking services. Everything is conveniently located in a single place.

Shopping malls are also popular social spaces. People often meet there to spend time together, have ice cream, drink coffee, or simply walk around and browse the stores ("window shopping," known in Colombia as *vitrinear*).

For this reason, shopping malls seek to collect as much information as possible about their customer's preferences, such as:

- What did they buy?
- How much money did they spend?
- Which stores did they shop at?

This data is usually collected through promotional raffles, in which customers register their purchase receipts for a chance to win prizes. As a result, one of the main methodological limitations of this study is that we do not have information on 100% of the purchases. Instead, the analysis is based on a sample of the transactions submitted by participating customers.

The objective of this project is to segment the shopping mall's customers using clustering techniques. The goal is to create customer profiles based on their purchasing behavior, enabling the mall to better understand different customer segments and support data-driven marketing and business decisions.

---

## Original dataset

The raw dataset contains **453,396 observations** and **14 variables**.

### Observations

- Each row represents a purchase receipt registered by a customer.

### Variables

- Year
- Quarter
- Customer ID
- Year-Month
- Transaction Date
- Transaction Type
- Purchase Amount
- Store
- Business / Establishment
- Gender

- Category
- Subcategory
- Day of the Week

## Version

![Pandas](https://img.shields.io/badge/pandas-2.3.2-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-2.3.4-013243?logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/seaborn-0.13.2-4C72B0)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.10.6-11557C?logo=matplotlib&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/scikit--learn-1.7.2-F7931E?logo=scikit-learn&logoColor=white)

_NOTE: The data original langague is spanish (Colombian's official language), we translate the columns names and rows before_
