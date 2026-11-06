# Sales Prediction & Forecast

Python FastAPI API for classical time-series style sales forecasting from CSV history.

Trains a lightweight regression model on monthly sales and returns forward projections for planning demos. No external LLM required.

## Stack

- **Backend:** Python 3.11+, FastAPI, Uvicorn
- **ML:** scikit-learn (Ridge), Pandas, NumPy
- **Frontend (optional demo UI):** React + Vite

## Features

- Upload or use bundled monthly sales sample data
- Forecast horizon with model-driven projections
- Clear JSON responses for charts and tables

## Quick start

```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload --port 8003
```

API docs: http://localhost:8003/docs

```bash
cd frontend
npm install
npm run dev
```

## Author

Pooja Sharma — [Pooja101117](https://github.com/Pooja101117)
