# Project A: Smart Inventory Forecasting

This project forecasts SKU-level demand, recommends reorder quantities, simulates stockouts and inventory costs, and displays results on a Streamlit dashboard.

## Key Features:
- ABC segmentation
- Prophet-based demand forecasting
- Reorder point logic
- Reorder simulation
- What-if analysis
- Streamlit dashboard

## Folder Structure:
- `/data`: raw and processed data
- `/src`: core logic modules
- `/notebooks`: Colab or Jupyter notebooks
- `/streamlit_app`: dashboard app

## Usage:
1. Fill in your CSV data under `data/raw/`
2. Run `notebooks/model_dev.ipynb` to process and forecast
3. Launch dashboard with `streamlit run streamlit_app/app.py`
