# Interpolation vs Extrapolation: LightGBM vs Linear Regression

- Train on **20–40°C** with small noise, evaluate on **0–100°C**
- Show that ML (especially tree ensembles) are **strong at interpolation** but **weak at extrapolation**
- Reproduce the figures in `fig/` by running the notebook

## Quickstart (local)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://github.com/cSAS3/ml-interp-extrap-lightgbm/blob/main/interp_vs_extrap_lightgbm.ipynb)
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
# open interp_vs_extrap_lightgbm.ipynb and run all
```

## Figures
- `fig1_ground_truth.png`
- `fig2_interp_vs_extrap.png`
- `fig3_abs_error.png`
