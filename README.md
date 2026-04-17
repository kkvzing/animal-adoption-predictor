# Animal Adoption Predictor

A machine learning tool that predicts adoption likelihood and estimated wait time for animals at the Long Beach Animal Shelter, built for shelter staff to use at intake time.

## Live App

[Insert Streamlit URL here]

## Run with Docker

```bash
docker build --no-cache -t animal-adoption-predictor .
docker run --rm -p 8501:8501 animal-adoption-predictor
```

Then open http://localhost:8501 in your browser.

## Run Locally

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run app/app.py
```

## Project Structure
