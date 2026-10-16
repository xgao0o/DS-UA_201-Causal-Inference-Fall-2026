# DS-UA 201: Causal Inference — Fall 2026

DS-UA 201 Causal Inference (Fall 2026)

## Lab notebooks

- [Week 1: Introduction to causal inference](labs/1-Introduction.ipynb)
- [Week 2: Probability, dependence, and conditioning](labs/2-Probability.ipynb)
- [Week 3: Statistics—estimation, sampling distributions, and inference](labs/3-Statistics.ipynb)
- [Week 4: Experiments—random assignment, estimation, and interpretation](labs/4-Experiments.ipynb)
- [Week 5: Regression—description, causality, and uncertainty](labs/5-Regression.ipynb)
- [Week 6: Natural experiments and midterm review](labs/6-Natural_Experiments.ipynb)

## Running a notebook

Upload the notebook to [Google Colab](https://colab.research.google.com/) and choose **Runtime → Run all**. Each notebook's 'Open in Colab' link works once that notebook has been published to the Fall 2026 GitHub repository; unpublished local notebooks must be uploaded manually.

**Week 4 also uses [data/nsw.dta](data/nsw.dta).** Upload this file in Colab's Files sidebar before running the notebook. Locally, keep the `data/` and `labs/` folders in their repository locations and launch the notebook from either the repository root or `labs/`.

**Week 5 uses synthetic data generated in the notebook** and requires no data upload. It adds `statsmodels` for regression standard errors, with a 60-minute core and optional polynomial ridge regression and clustered-standard-error extensions.

**Week 6 also uses [data/FinalAnon.dta](data/FinalAnon.dta)** for the historical Dutch Postcode Lottery example, copied unchanged from the Spring 2025 course materials. Upload it in Colab’s Files sidebar, or keep `data/` and `labs/` in their repository locations when running locally. The notebook includes a 60-minute combined session: 30 minutes on natural experiments and a 30-minute guided midterm review. Its 15 original exam-style questions have individually collapsible solutions; extra questions and the control-variable/independence extensions are available for further practice. Synthetic examples require no downloads. It uses the same dependencies as Week 5 and preserves the original authors’ attribution.

Alternatively, in a local environment, use Python 3.10 or later. In an activated virtual environment, install the dependencies and start Jupyter:

```bash
python -m pip install jupyterlab numpy pandas matplotlib scipy statsmodels
python -m jupyter lab
```

Open the notebook, then choose **Restart Kernel and Run All Cells**. Saved outputs are included for reading without execution.
