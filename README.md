# House Price Predictor

A Machine Learning project that predicts house prices using a trained model and Gradio interface.

## Live Demo

Try the deployed application here:

https://huggingface.co/spaces/sahasra-15/house-price-predictor

## GitHub Repository

This repository contains the source code and files required for the House Price Predictor project.

## Technologies Used

- Python
- Scikit-learn
- Pandas
- Gradio
- Hugging Face Spaces# House Price Predictor: Build, Train & Deploy ML Models

A hands-on workshop notebook that predicts Ames, Iowa house prices (2006–2010) and turns the trained pipeline into a Gradio app deployed on Hugging Face Spaces. It is a learning project, not a real-world valuation service.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Put `train.csv` in `data/` (see [data/README.md](data/README.md)).

## Workshop

Open `house_price_prediction.ipynb` and run it from top to bottom. Everything happens in the notebook:
it also writes `feature_engineering.py` (Step 5), `artifacts/` (Step 11) and `app.py` (Step 12).

## Run the app

```bash
python app.py
```

Then open http://127.0.0.1:7860. Deployment to Hugging Face Spaces is covered in Step 13 of the notebook.
