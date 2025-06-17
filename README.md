# aipipeline1

This repo contains a simple, three step AI pipeline for OpenShift AI along with a deployment YAML for a local instance of Minio (for S3 storage).

To use this, create the minio instance via the minio.yaml file, and then set it up as a connection in OpenShift AI. Create a workbench with a 'Standard Data Science' image, clone this repo, upload a kaggle.json (token for kaggle.com) into the local file space of the workbench, and then run the pipeline.
