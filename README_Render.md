# Hello World Motion Lab — Render

This is a Flask app and does not depend on Streamlit.

## Deploy
1. Upload `app.py`, `requirements.txt`, and `render.yaml` to the root of a GitHub repository.
2. On Render, choose **New + → Web Service** and connect the repository.
3. Set build command to `pip install -r requirements.txt`.
4. Set start command to `gunicorn app:app`.
5. Deploy the service.

You can alternatively create a Render Blueprint from the included `render.yaml`.
