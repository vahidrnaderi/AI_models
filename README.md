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

Binder builds from `environment.yml` (Python 3.10, CPU-only PyTorch + conda `fastai`). The `start` script launches Voilà automatically — leave **File** as default on mybinder.org.

First launch rebuilds the image (~5–15 min). A **424 error** after a successful build usually means the session crashed at startup (often out-of-memory) — open the link again for a fresh session.
