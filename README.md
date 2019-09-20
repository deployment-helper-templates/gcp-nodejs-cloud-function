# gcp-nodejs-cloud-function
This template is used to deploy a cloud function on GCP with Cricle CI pipeline. 

## Steps to taken before deployment
Rename `explorts['gcs_project_name']` to `exports['APP_NAME']` in `index.js` file
### Env Variables 
* `DEV_GCLOUD_ACCOUNT_KEY` GCP service account key json

* `APP_NAME` function name to deploy same as `modules.app_name` 

* `RUN_TIME` Application run time like `nodejs10` 

* `GCP_PROJECT_NAME` Google cloud project name.
