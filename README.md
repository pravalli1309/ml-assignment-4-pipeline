# ML Assignment 4 End-to-end pipeline

Notebook: `assignment4_endtoend.ipynb` (run top to bottom with Runtime -> Restart and run all).
Files: `Bengaluru_House_Data.csv` (raw data), `bengaluru_clean.csv` (cleaned data), `pipeline.joblib` (fitted pipeline).

## Dataset
Bengaluru House Price Data. Target: `price` (lakhs of rupees). No model is trained.
Source: https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data

## Before and after
| | Raw file | Final |
|---|---|---|
| row count | 13320 | 12027 |
| column count | 9 | 209 |
| missing value count | 6201 | 0 |
| duplicate count | 529 | 97 |

Final duplicate count is measured on the cleaned data; final column count is the width of the model-ready matrix.

Shapes: X_train (9621, 209), X_test (2406, 209), y_train (9621,), y_test (2406,)
