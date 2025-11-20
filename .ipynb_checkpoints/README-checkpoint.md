# HM Fashion Recommendations

Applied deep-learning exploration of the H&M fashion recommendations dataset.

## Quickstart

**Clone the repo**

```bash
git clone https://github.com/IlMalakhov/HM-fashion-recs.git
cd HM-fashion-recs
```

| Step | Local (README) | JupyterHub |
|------|----------------|-------------|
| Create environment | ```bash\npython3 -m venv .venv\nsource .venv/bin/activate  # Windows: .\\.venv\\Scripts\\activate\n``` | Use the preinstalled Python on JupyterHub (no venv needed). |
| Install dependencies | ```bash\npip install --upgrade pip\npip install -e .\n``` | Install through notebooks |
| Access project data | Maybe we could ask for a bucket | ```bash\nln -s /home/jovyan/__DATA/APBDID_F25/data/handm/ /home/jovyan/HM-fashion-recs/data\n``` |
