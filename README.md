# gcp_model_deploy_example

Code for [Deploy Your ML Model as a Web Service in Minutes Using GCP’s Cloud Run](https://medium.com/p/ee9d433d8787)

## Create Env
```commandline
conda create --name gcp_model_deploy python==3.8
conda activate gcp_model_deploy
```

## Install dependencies
```commandline
poetry install
```

## Deployment

Activate cloudbuild in your GCP project

we can just run `make run_grc_build` to build and push the dockerized API to GCP.

We can just run `make cloud_run_deploy` to deploy the app to Cloud run in less than a minute.
