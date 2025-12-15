# Neuralk API Notebook Examples

This repository contains client-facing notebooks that demonstrate how to onboard with the Neuralk API and run NICL on sample datasets. Use these notebooks as hands-on guides to create an organization, add users, and compare NICL to a traditional baseline.

## Quickstart
- Open in Colab: [organisation_creation_and_inference_first_example.ipynb](https://colab.research.google.com/github/NeuralkAI/neuralk-notebooks/blob/main/organisation_creation_and_inference_first_example.ipynb)  
- Run all cells in order; credentials are defined inside the notebook for demo convenience.

## Notebook overview
- `organisation_creation_and_inference_first_example.ipynb`
  - Install dependencies once.
  - (Guarded) create an organization and first admin user with Neuralk.
  - Authenticate with the Neuralk client and inspect organization details.
  - Optionally add a second user.
  - Synthetic quickstart: deterministic NICL classification example.
  - Real dataset demo (OpenML) with preprocessing via `TableVectorizer`.
  - Benchmark comparison against an XGBoost baseline.

## Running locally
1. Ensure Python 3.10+ and Jupyter are available.
2. Open the notebook in your preferred environment.
3. Fill the credential variables (`ACCESS_CODE`, `ORGANIZATION_NAME`, `ADMIN_EMAIL`, `ADMIN_PASSWORD`).
4. Flip the guard flags (`RUN_ACCOUNT_CREATION`, `RUN_USER_CREATION`) only when you want to provision resources.
5. Execute cells top-to-bottom.

## Notes
- The notebook keeps secrets inline for demo purposes; avoid committing real credentials to shared repos.

