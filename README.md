# Cat or Dog classifier (Voilà)

Two notebooks:


| Notebook                     | Use                                 |
| ---------------------------- | ----------------------------------- |
| `01_cat_or_dog-local.ipynb`  | **Local** development (Python 3.12) |
| `01_cat_or_dog-binder.ipynb` | **Binder** / shared Voilà app       |


## Local

```bash
conda env create -f environment.yml   # first time only
conda activate AI_models
voila 01_cat_or_dog-local.ipynb
```

Voilà starts a local web server and prints a URL (usually `http://localhost:8866`). Open that link in your browser — or let it open automatically — and you’ll see the **Cat or Dog** app: upload a photo, click **Classify**, and get the prediction. The first run may take a minute while the model loads.

Pinned deps are in `requirements.txt` (`fastai`, `ipywidgets`, `voila`).

## Binder

**Launch the app:**

[https://mybinder.org/v2/gh/vahidrnaderi/AI_models/main?urlpath=%2Fvoila%2Frender%2F01_cat_or_dog-binder.ipynb](https://mybinder.org/v2/gh/vahidrnaderi/AI_models/main?urlpath=%2Fvoila%2Frender%2F01_cat_or_dog-binder.ipynb)

Binder builds from `environment.yml` (Python 3.12, CPU PyTorch + `fastai` via pip). The Voilà path is:

```
/voila/render/01_cat_or_dog-binder.ipynb
```

On [mybinder.org](https://mybinder.org), paste the repo URL and set **urlpath** to `/voila/render/01_cat_or_dog-binder.ipynb` (or use the launch link above).

First launch rebuilds the image (~5–15 min). Loading the model can take another minute after the page opens.
