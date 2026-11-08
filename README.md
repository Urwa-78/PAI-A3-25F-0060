# PAI-A3 – Programming for AI, Assignment 3

## How to Run
Install Python 3 along with NumPy, pandas, matplotlib, and Jupyter Notebook. Keep the `data/` folder in the same directory as the notebook. Open `Assignment3_Programming_for_AI.ipynb` in Jupyter Notebook or VS Code, then select Kernel → Restart and Run All to execute all cells.

The notebook generates the following files in the `outputs/` directory:
 `dashboard.png`
`dashboard.pdf`
 `wave.gif`

## One Thing That Was Challenging
Handling the weather dates was one of the most challenging parts of this assignment. The dataset contained two different date formats, and using `pd.to_datetime` directly incorrectly interpreted 23 out of 60 DD/MM/YYYY dates as month-first. I handled this by parsing each date format separately and validating the converted results.