# Capstone
link: https://github.com/abbhinavvashist/UdacityCapstoneFinal
## Project Overview
This Capstone project will utilize CI/CD and cloud services learned during the Udacity - AWS Cloud DevOps Engineer nanodegree.

## Steps
- Create Dockerfile
- Circleci pipeline runs lint tests on Dockerfile to ensure Dockerfile is suited to be uploaded to repository
- Dockerfile is built and then uploaded to Docker repository automatically by CircleCi using preconfigured scripts.
- EKS cluster is deployed automatically by CircleCI using AWS Cli - status of creation of EKS cluster can be viewed in Cloudformation
- Docker application which was uploaded to Docker repository is deployed in EKS cluster by using Kubernetes Cli.

## Requirements
You will need to configure the following variables in your CircleCi project:
- AWS_ACCESS_KEY_ID
- AWS_DEFAULT_REGION
- AWS_SECRET_ACCESS_KEY
- DOCKER_LOGIN
- DOCKER_PASSWORD


Output

I can use my cluster endpoint to check the running application.

http://a13f90bb518c546f38cd353201a88bfb-1304169613.us-east-1.elb.amazonaws.com/
