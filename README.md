# AI Developer Interview — Onsite Starter Kit

This folder gives you a ready-to-run environment for your 35–70 minute live coding segments.

## Contents
- `interview.ipynb` — The main notebook with cells for Python/Pandas, NLP, and a tiny retrieval/SQL-style demo.
- `data/` — Small CSV datasets used by the notebook.
- `requirements.txt` — Minimal Python deps (Jupyter, pandas, scikit-learn, transformers, torch).

## Quick Start (Local)
```bash
# 1) Create & activate a fresh venv (Windows uses Scripts\activate)
python -m venv interview-env
source interview-env/bin/activate

# 2) Install deps (if PyTorch is too large for your machine, comment it out in requirements.txt)
pip install -r requirements.txt

# 3) Launch Jupyter
jupyter notebook  # or: jupyter lab
```

Then open **`interview.ipynb`** and follow the section prompts.

## Optional (Colab)
You can also upload `interview.ipynb` and the `data/` folder to Google Drive and run it in Colab.
If you do this, install deps in the first cell:
```python
!pip -q install pandas scikit-learn transformers torch
```

## Tips for Interviewers
- Keep the focus on reasoning and clarity, not only the final answer.
- Time-box each section.
- If the model download is slow, allow candidates to implement a quick heuristic baseline (e.g., simple word list) and then discuss how they'd swap in a transformer later.
