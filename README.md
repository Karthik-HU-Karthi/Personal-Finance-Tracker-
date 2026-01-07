# Personal Finance Tracker

A lightweight Python application for managing personal finances. This tool analyzes income and expense data to provide monthly summaries, net savings calculations, and visual distributions of spending habits.

##  Project Overview
The goal of this project is to provide a clear picture of financial health by:
* **Data Processing:** Converting raw transaction strings into actionable datetime objects.
* **Monthly Summaries:** Grouping data to calculate total income vs. total expenses per month.
* **Savings Analysis:** Automatically calculating net savings for each period.
* **Visualizations:** Using Matplotlib and Seaborn to generate:
    * Bar charts for Income vs. Expense comparisons.
    * Pie charts for spending distribution by category (Food, Utilities, etc.).

##  Dataset Structure
The project expects a `personal_finance.csv` file with the following columns:
* `Date`: Format `YYYY-MM-DD`
* `Description`: Transaction details
* `Category`: (e.g., Food, Salary, Transport)
* `Amount`: Numeric value (Negative for expenses, Positive for income)
* `Type`: String ('Income' or 'Expense')

##  Getting Started

### Prerequisites
* Python 3.8+
* Jupyter Notebook or Google Colab

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/Karthik-HU-Karthi/first-repo.git](https://github.com/Karthik-HU-Karthi/first-repo.git)
