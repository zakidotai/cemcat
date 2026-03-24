# CemCat Streamlit Hosting Bundle

This folder is ready to be pushed to GitHub and deployed on Streamlit Cloud.

## Files included

- `streamlit_app.py` (main app)
- `requirements.txt`
- `data/ner_cems_40k.csv`
- `data/pii_abs.json`
- `data/clinker_comps_with_dates.csv`
- `upload/composition_cls_slag_updated.csv`

## Local run

```bash
streamlit run streamlit_app.py
```

## Streamlit Cloud setup

1. Push this folder to your GitHub repository.
2. In Streamlit Cloud, create a new app and point to:
   - Repository: your repo
   - Branch: your target branch
   - Main file path: `streamlit_hosting_bundle/streamlit_app.py`
