# Neuralk API Notebook Examples

This repository contains client-facing notebooks that demonstrate how to use the Neuralk API and run NICL on sample datasets.

## Getting Started

1. Get your API key at https://prediction.neuralk-ai.com/register (format: `nk_live_xxxxxxxxxxxx`)
2. Set your API key:
   ```bash
   export NEURALK_API_KEY=nk_live_your_api_key_here
   ```
3. Open a notebook in Colab and run all cells

## Notebooks

- `introduction-to-neuralk-api.ipynb` - [Open in Colab](https://colab.research.google.com/github/NicolasNeuralkAI/neuralk-notebooks/blob/main/introduction-to-neuralk-api.ipynb)
  - **Recommended starting point** for using NICLClassifier with API key auth.
  - Demonstrates NICLClassifier on synthetic and real-world housing data.
  - Shows preprocessing pipeline with TableVectorizer and scaling.
  - Compares NICL performance against gradient boosting baseline.

- `explainability-with-neuralk.ipynb` - [Open in Colab](https://colab.research.google.com/github/NicolasNeuralkAI/neuralk-notebooks/blob/main/explainability-with-neuralk.ipynb)
  - Interpret and explain NICLClassifier predictions using prediction probabilities, confidence analysis, permutation importance, and SHAP values.
  - Uses the housing dataset to demonstrate model-agnostic explainability techniques.

- `on-premise-server.ipynb` - [Open in Colab](https://colab.research.google.com/github/NicolasNeuralkAI/neuralk-notebooks/blob/main/on-premise-server.ipynb)
  - For on-premise deployment scenarios.

## Running locally

1. Ensure Python 3.10+ and Jupyter are available.
2. Install the SDK: `pip install neuralk`
3. Set your API key: `export NEURALK_API_KEY=nk_live_...`
4. Open the notebook and execute cells top-to-bottom.
