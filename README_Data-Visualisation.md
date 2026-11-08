# AI, Data Science and Software Development Jobs in the USA – Data Visualisation

Python / Jupyter project for the **Data Visualisation** module, CCT College Dublin (2026).
Grade: *pending*.

## What it does
Cleans and analyses the US Bureau of Labor Statistics (BLS) *Occupational Employment and Wage Statistics* data (May 2023, 413,327 rows) for 12 occupations in software, data systems, data science and AI/computing research. It then builds **seven visualisations** (bar, pie, grouped bar, box, scatter, 3D scatter) and a **2015–2025 time series**.

Highlights: handling of placeholder symbols (`*`, `**`, `#`), duplicate/hierarchy checks, outlier testing with the IQR method, and honest notes on the limits of the data (for example the $239,200 salary cap).

## Tools
Python 3.10+, pandas, NumPy, Matplotlib, Seaborn, Plotly, openpyxl, Jupyter.

## How to run it on your computer

**1. Install Python** (3.10 or newer) from https://www.python.org/downloads/ . On Windows, tick *"Add Python to PATH"* during installation.

**2. Download this repository**: click the green **Code** button, then **Download ZIP**, and unzip it. (Or run `git clone <this-repo-url>`.)

**3. Open a terminal in the project folder** and install the libraries:
```bash
pip install pandas numpy matplotlib seaborn plotly openpyxl notebook
```

**4. Get the data files.** Keep these Excel files in the **same folder as the notebook**:
- `all_data_M_2023.xlsx` – May 2023 OEWS data (sheet "All May 2023 data")
- `national_2015.xlsx` … `national_2025.xlsx` – one national file per year

They are public BLS files, available at https://www.bls.gov/oes/tables.htm . 

**5. Start Jupyter and run the notebook:**
```bash
jupyter notebook
```
Open `CA1-Data-Visualisation-2023302-Wanderson-Lucas-Ohenes.ipynb` and choose **Kernel → Restart & Run All**.

## Author
Wanderson Lucas Ohenes – Student number 2023302 – [GitHub](https://github.com/wlucasohenes)
