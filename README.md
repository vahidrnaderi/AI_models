# Cat or Dog classifier (Voilà)

## Local (Python 3.14)

```bash
conda env create -f environment.local.yml   # first time only
conda activate AI_models
jupyter lab 01_cat_or_dog.ipynb
```

Run cells 1–5 in order after a kernel restart.

Pinned deps are in `requirements.txt` (`fastai`, `ipywidgets`, `voila`).

## Binder

https://mybinder.org/v2/gh/vahidrnaderi/AI_models/main

Binder builds from `environment.yml` (Python 3.10, CPU-only PyTorch + conda `fastai`). The server starts with `jupyterhub-singleuser` and opens Voilà via `default_url` — leave **File** as default on mybinder.org.

Alternative direct Voilà URL:

```
?urlpath=voila%2Frender%2F01_cat_or_dog.ipynb
```

First launch rebuilds the image (~5–15 min). Loading the model can take another minute after the page opens.
