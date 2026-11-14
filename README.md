# County Rainfall and Planting Advisory

**Author:** Asman Makero Musa · PLP Data Analytics Cohort 7  
**Repository:** [plp-da-a2-rainfall-advisory](https://github.com/makeromusa/plp-da-a2-rainfall-advisory)

---

## Project Summary

This project cleans and analyzes monthly rainfall records (January–December) for five Kenyan counties (Nairobi, Nakuru, Kisumu, Mombasa, and Machakos) to determine annual rainfall totals, monthly averages, wettest months, dry-month counts, and optimal two-month planting windows. It handles manual data entry errors in Machakos records using Python exception handling and computes vectorised metrics using NumPy without explicit loops.

---

## How to Run

Open the notebook directly in Google Colab and select **Runtime → Run all** (or `Ctrl + F9`):  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makeromusa/plp-da-a2-rainfall-advisory/blob/main/rainfall_analysis.ipynb)

To run locally:
```bash
pip install -r requirements.txt
jupyter notebook rainfall_analysis.ipynb
```

---

## Planting Advisory

1. **Central & Western Regions (Nairobi, Nakuru, Kisumu)**: Target planting during the **Apr-May** long-rains window when cumulative two-month rainfall peaks between 265 mm and 420 mm, with Kisumu leading all counties with an annual total of 1,371 mm and zero dry months (<50 mm).
2. **Coastal Region (Mombasa)**: Plant during the **Apr-May** window (390 mm combined) anchored by May as the peak wettest month at 240 mm to ensure crop establishment before dry conditions arrive.
3. **Eastern Semi-Arid Region (Machakos)**: Restrict planting strictly to the **Nov-Dec** short-rains window (278 mm combined) driven by the November peak of 182 mm, as the county endures 6 dry months under 50 mm.
