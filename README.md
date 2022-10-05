# java-basic-container
Basic java app to test lambda using containers

## How to upload container to ECR:
* `docker build -t basic-java:latest .`
* `docker tag basic-java:latest [ECR PATH]/basic-java:latest`
* `docker push [ECR PATH]/basic-java:latest`
