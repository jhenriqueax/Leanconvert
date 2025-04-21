
# A/B Test Funnel Analysis

This notebook analyzes raw A/B test data from an e-commerce experiment. It compares how users interacted with two homepage variants (A and B) by counting unique users and calculating conversion rates for each funnel step.

## What It Does

- Loads test data from an Excel file
- Counts:
  - Unique visitors per variant (A and B)
  - Number of users who performed each action:
    - Product Page View
    - Add to Basket
    - Checkout
    - Purchase
    - App Downloads
- Calculates:
  - Conversion Rate (CR) for each action

## Tech Stack

- Python
- pandas, numpy

## How to Run

1. Install dependencies:
   ```bash
   pip install pandas numpy openpyxl
   ```

2. Edit the path to the Excel file in the notebook:
   ```python
   path = "/your/path/to/raw_data.xlsx"
   ```

3. Run the notebook.

