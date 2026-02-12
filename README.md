# Connecticut Real Estate Sales Analysis (Python EDA)

Exploratory data analysis of Connecticut real estate sales using **pandas** to clean, aggregate, and visualize trends in sales volume, pricing behavior, and assessed vs sale value dynamics.

## Case Study (visual write-up)
https://krrusha.github.io/Connecticut-Real-Estate-Analysis/

> Note: For the full notebook workflow and code, see **analysis.ipynb** in this repo.



## Highlights
- Compared **total property sales vs sales below assessed value** across years to identify market stress periods.
- Focused housing-only trends to isolate how the **residential market** behaves over time.
- Compared housing price patterns by type to understand **changing market mix**.
- Evaluated commercial behavior across towns by comparing **assessed value vs sale amount**.



## Tech Stack
- Python (pandas, numpy)
- Matplotlib
- Jupyter Notebook



## Data Source
Real Estate Sales 2001–2018 (Data.gov):  
https://catalog.data.gov/dataset/real-estate-sales-2001-2018

Dataset file used in this repo:
- `Real_Estate_Sales_2001-2023_GL.csv`



## Repository Structure
```text
.
├── index.html              # Case study page (charts + insights)
├── analysis.ipynb          # Full notebook (cleaning + analysis)
├── analysis_files/         # Exported figures used by index.html
└── Real_Estate_Sales_2001-2023_GL.csv
