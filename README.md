# GithubWrapped 


## Install Instructions 
#### Setup virtual env
```bash
conda create -n githubwrapped python-3.6 anaconda 
conda activate githubwrapped
```
#### Install requirments
```bash 
pip install -r requirments.txt
```
#### Install GCP 
Go through steps here for your OS / container
- https://cloud.google.com/sdk/docs/install
#### Setup GCP
```bash 
gcloud auth application-default login
gcloud services enable bigquery.googleapis.com
gcloud services list
```
## Obtaining Github Access Token 
- https://github.com/settings/tokens

## Project Goals
![image](https://github.com/fdac23/GithubWrapped/assets/21347911/e7bc4e25-0dea-473e-ab20-d2ace1d3b61e)


## Resources
- https://www.kaggle.com/code/poonaml/analyzing-3-million-github-repos-using-bigquery
- https://cloud.google.com/docs/authentication/provide-credentials-adc#how-to
