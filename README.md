# Gikomba Market Stall Performance Analysis

**Name:** Collins Kipngetich Basuben
**Cohort:** PLP Data Analytics

## Business problem

Wanjiku runs a fresh-produce stall at Gikomba Market. For two weeks she wrote her daily sales in a notebook and kept a rough record of her stock. She hired me as a freelance analyst to answer four questions: how is the business doing, is it growing, what should she restock, and where should she focus her effort? I answer them with core Python only (no pandas or NumPy), covering sales totals and averages, week-on-week growth, strong and weak days, weekday versus weekend sales, low stock and gross margin per product.

## How to run

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Basuben/plp-da-a1-gikomba-stall-analysis/blob/main/stall_analysis.ipynb) Open `stall_analysis.ipynb` in Colab and choose Runtime > Run all. No extra packages are needed.

## Top three findings

1. **Weekends sell far more.** Saturday and Sunday average KES 4,900 a day against KES 2,685 on weekdays, which is 82.5% more.
2. **The business is growing.** Sales rose from KES 22,050 in week 1 to KES 24,400 in week 2, a week-on-week growth of 10.66%.
3. **Two products need restocking now.** Tomatoes (18 kg against a reorder level of 25 kg) and Sukuma (9 kg against 15 kg) are below their reorder levels, and 2 of the 5 products are affected.

## Files

- `stall_analysis.ipynb`: the full analysis, the printed Stall Performance Report and recommendations for Wanjiku.
