
# Deepfake Detector (PyTorch)

## Run locally
python -m venv venv
source venv/bin/activate
pip install -r backend/requirements.txt
cd backend
uvicorn app:app --reload --host 0.0.0.0 --port 8000

Open frontend/index.html in any browser.

Replace model weight paths in app.py before production.
