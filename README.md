# S3 Docker



# Abstract
This is a sample repository for accessing to aws s3 buckets via docker (with VSCode).



# Prerequisites
- docker 
- docker-compose


# procedure
1. from aws IAM console, create a new user with programmatic access to s3.
  - https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_examples_s3_rw-bucket-console.html

2. install docker plugin `rexray:s3fs` with the user's accesskey and secretkey.
  

3. edit `env/docker/docker-compose.yml` to add s3 buckets to mount them on docker container.