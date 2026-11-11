# mslearn-mlops

My working copy of the Microsoft Learn MLOps challenges: end-to-end machine learning operations with Azure Machine Learning and GitHub Actions. The lab content is based on [MicrosoftLearning/mslearn-mlops](https://github.com/MicrosoftLearning/mslearn-mlops).

## Contents

| Path | Purpose |
| --- | --- |
| `docs` | Lab instructions, from experimentation through deployment and monitoring |
| `experimentation` | Notebooks for training, MLflow tracking, hyperparameter tuning, pipelines and AutoML |
| `src` | Training script, job definition and online endpoint deployment |
| `infra` | Scripts to set up the Azure Machine Learning resources |
| `.github/workflows` | Workflows that train in dev and prod and deploy to production |

## Requirements

An Azure subscription with an Azure Machine Learning workspace, and Azure credentials stored as GitHub secrets for the workflows.
