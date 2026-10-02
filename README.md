# DS-UA 201: Causal Inference — Fall 2026

DS-UA 201 Causal Inference (Fall 2026)

## Lab notebooks

- [Week 1: Introduction to causal inference](labs/1-Introduction.ipynb)
- [Week 2: Probability, dependence, and conditioning](labs/2-Probability.ipynb)
- [Week 3: Statistics—estimation, sampling distributions, and inference](labs/3-Statistics.ipynb)
- [Week 4: Experiments—random assignment, estimation, and interpretation](labs/4-Experiments.ipynb)

## Running a notebook

Upload the notebook to [Google Colab](https://colab.research.google.com/) and choose **Runtime → Run all**. Each notebook's 'Open in Colab' link works once that notebook has been published to the Fall 2026 GitHub repository; unpublished local notebooks must be uploaded manually.

**Week 4 also uses [data/nsw.dta](data/nsw.dta).** Upload this file in Colab's Files sidebar before running the notebook. Locally, keep the `data/` and `labs/` folders in their repository locations and launch the notebook from either the repository root or `labs/`.

Alternatively, in a local environment, use Python 3.10 or later. In an activated virtual environment, install the dependencies and start Jupyter:

```bash
python -m pip install jupyterlab numpy pandas matplotlib scipy
python -m jupyter lab
```

Open the notebook, then choose **Restart Kernel and Run All Cells**. Saved outputs are included for reading without execution.
