# Copilot Instructions for full-stack-machine-learning

## Project Overview
- This repository contains structured Jupyter Notebooks and datasets for the "Full Stack Machine Learning" course (Digethic Data Scientist / AI-Engineer).
- All course content is under `notepads/`, organized by module and topic. Each subfolder contains template (`Vorlage_`), solution (`Lösung_`), and example (`Beispiele_`) notebooks.
- Datasets for exercises are in `data/` and sometimes duplicated in module folders for convenience.

## Key Workflows
- **Setup:**
  - Windows: Run `setup.ps1` (use `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser` if needed).
  - Linux/Mac: Run `setup.sh`.
- **Python Environment:**
  - Activate with `.venv\Scripts\Activate.bat` (Windows) or `source .venv/bin/activate` (Linux/Mac).
  - Install new dependencies with `pip install <package>` and update `requirements.txt` using `pip freeze > requirements.txt`.
- **Jupyter Notebooks:**
  - Start with `jupyter lab --ip=127.0.0.1 --port=8888`.
  - Notebooks are the primary development and learning format. Follow the structure: import, data load, model, evaluation, visualization.

## Project Conventions
- **Naming:**
  - Notebook files use German prefixes: `Vorlage_` (template), `Lösung_` (solution), `Beispiele_` (examples).
  - Module folders are numbered and named by topic (e.g., `B04_Einführung_Python`).
- **Code Style:**
  - Use standard Python (PEP8) and idiomatic NumPy, pandas, and scikit-learn patterns.
  - Visualizations use `matplotlib` by default; advanced plots may use `seaborn` or `plotly`.
- **Data:**
  - Use provided CSVs in `data/` or module folders. Paths are relative to the notebook location.

## Integration & Dependencies
- Core libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `plotly`, `jupyter`.
- Deep learning: `pytorch`, `tensorflow`, `keras` (used in advanced modules).
- No custom Python packages or internal APIs—focus is on standard open-source tools.

## Examples
- See `notepads/Basismodule/B07_Gradientenverfahren/B07_Vorlage_ Gradientenverfahren.ipynb` for a typical exercise structure: import, data, model, training loop, error visualization.
- Each module's `Lösung_` notebook provides a reference solution.

## Tips for AI Agents
- When generating new notebooks, match the folder/module structure and naming conventions.
- Prefer code cells with clear comments in German, as in existing notebooks.
- When referencing data, use relative paths and check for duplicates in module folders.
- For new dependencies, update `requirements.txt` and document in the notebook.

---
For more context, see `README.md` and explore the `notepads/` directory for module organization and coding style.
