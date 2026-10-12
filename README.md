# Three Targets, 194 Realities

Exploratory data analysis of the WHO Triple Billion targets, 2018–2025.

## Files

| File | Description |
| --- | --- |
| `Three_targets__194_realities_-_Scarlette_Alcaraz.ipynb` | Jupyter notebook with the full analysis |
| `dataset.csv` | WHO Triple Billion data used by the notebook |

## Requirements

- Python 3.9 or later
- The following libraries:

| Library | Used for |
| --- | --- |
| `pandas` | Loading and transforming the data |
| `numpy` | Numerical operations |
| `matplotlib` | Charts |
| `seaborn` (0.13 or later) | Chart styling, boxplots and line charts by group |
| `jupyter` | Running the notebook |

## Installation

1. Download or clone this repository:

   ```bash
   git clone https://github.com/scarlette19991989/Three-targets-194-realities.git
   cd Three-targets-194-realities
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate        # macOS / Linux
   .venv\Scripts\activate           # Windows
   ```

3. Install the dependencies:

   ```bash
   pip install pandas numpy matplotlib "seaborn>=0.13" jupyter
   ```

## How to run

1. Make sure `dataset.csv` is in the **same folder** as the notebook.
2. Start Jupyter:

   ```bash
   jupyter notebook
   ```

3. Open `Three_targets__194_realities_-_Scarlette_Alcaraz.ipynb`.
4. Run all cells from top to bottom: **Kernel › Restart & Run All** (or **Run › Run All Cells** in JupyterLab).

The notebook creates a `figures/` folder automatically and saves the 9 charts there as PNG files.

### Other ways to run it

- **VS Code:** install the *Python* and *Jupyter* extensions, open the notebook, select a Python interpreter with the dependencies installed and click **Run All**.
- **Google Colab:** upload the notebook to [colab.research.google.com](https://colab.research.google.com), then upload `dataset.csv` in the *Files* panel before running all cells. The libraries are already installed in Colab.

## Data source

World Health Organization, [Triple Billion dashboard](https://data.who.int/dashboards/global-progress/triple-billion?m49=001) (statistical release of 18 May 2026, CC BY 4.0).
