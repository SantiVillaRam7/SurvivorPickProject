# NFL Survivor Picks 2025

This repo scrapes the NFL schedule/results, aggregates moneyline odds, pulls weekly power rankings (CBS, FOX, NFL.com), and produces **Best Probability** and **Best Value** picks per week.

## Quickstart

### Prereqs
- Python 3.10–3.12
- Git
- (Optional) Conda/Mamba

### 1) Clone & set up environment

#### Option A: Built-in venv (recommended)
```bash
# Create the conda environment
conda env create -f environment.yml

# Activate the environment
conda activate nfl-survivor-2025

# Register the environment as a Jupyter kernel
python -m ipykernel install --user --name=nfl-survivor-2025 --display-name "Python (nfl-survivor-2025)"
