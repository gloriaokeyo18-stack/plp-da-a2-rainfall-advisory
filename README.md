# Rainfall Analysis and Planting Advisory

## Project Overview
This project analyses monthly rainfall data from five Kenyan counties: Nairobi, Nakuru, Kisumu, Mombasa and Machakos. Using Python and NumPy, it calculates annual rainfall totals, monthly averages, wettest months, dry-month counts and the best consecutive two-month rainfall windows. The analysis also handles missing and invalid rainfall entries in the Machakos dataset.

## How to Run
1. Open the Jupyter Notebook (`.ipynb`) in Google Colab.
2. Ensure NumPy is available in the environment.
3. Select **Runtime → Run all** to execute the notebook from beginning to end.
4. The notebook generates `rainfall_summary.csv`, containing the county-level results.

## Planting Advisory
- April–May is the strongest historical two-month rainfall window for Nairobi, Nakuru, Kisumu and Mombasa.
- Machakos records its strongest two-month window in November–December, suggesting a different potential planting advisory period.
- Farmers should confirm local rainfall onset, consult current forecasts and consider soil conditions before planting; these historical results are not forecasts.

## Data Quality
Two missing or invalid Machakos readings were replaced with the rounded mean of the ten valid observations (68 mm). This imputation may influence the county's calculated results.

## Tools Used
- Python
- NumPy
- CSV module (Python standard library)
- Google Colab
