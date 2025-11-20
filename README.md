# HM Fashion Recommendations

Applied deep-learning exploration of the H&M fashion recommendations dataset.

## Quickstart

**Clone the repo**

```bash
git clone https://github.com/IlMalakhov/HM-fashion-recs.git
cd HM-fashion-recs
```

| Step | Local | JupyterHub |
|------|----------------|-------------|
| Create environment | `python3 -m venv .venv` Mac/Linux: `source .venv/bin/activate` or Windows:`.\.venv\Scripts\activate` | Use the preinstalled Python on JupyterHub (no venv needed). |
| Install dependencies | `pip install --upgrade pip; pip install -e .` | Can probably install dependencies globally with `pip install` like usual |
| Access project data | Maybe we could ask for a bucket | Shortcut link to data/ `ln -s /home/jovyan/__DATA/APBDID_F25/data/handm/ /home/jovyan/HM-fashion-recs/data` |
