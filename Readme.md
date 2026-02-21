# MLG381A1 — Student Performance Analysis

Short project README for the repository.

## What this is

This repository contains Python scripts and notebooks for analyzing student performance data (CSV) and preparing models/analysis for a coursework project.

Key files:
- `App.py` — main application / runner (if present).
- `Analysis.py`, `Evaluations.py`, `Prep_Data.py`, `OddValueHandler.py` — helper modules for data preparation and evaluation.
- `Student_performance_data.csv` — dataset used by the scripts.
- `requirements.txt` — Python dependencies.

## Quick start

1. Create and activate a virtual environment (recommended):

   Windows (PowerShell):

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

2. Install dependencies:

   ```powershell
   pip install -r requirements.txt
   ```

3. Run the main script (example):

   ```powershell
   python App.py
   ```

Adjust the command above if your entrypoint is different (for example, run notebooks in `Notebooks/`).

## Notes

- This README was added to provide basic usage instructions.
- The repository previously contained compiled Python bytecode in `__pycache__` directories; those files have been removed and a `.gitignore` has been added to prevent them from being committed.

## Contact

If you need anything else changed or more detailed instructions (tests, examples, or CI), open an issue or ask here.
Project by 
Tyler Geuens 600153
Francois Myburg 600576
Marco Reinres 578056
Luan Mahoney 600617
