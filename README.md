<include a CircleCI status badge, here>

![mplisz](https://circleci.com/gh/mplisz/AWS-Microservices-Project.svg?style=svg)(https://app.circleci.com/pipelines/github/mplisz/AWS-Microservices-Project)

## Project Overview

This project concludes course 5 (Machine Learning Microservice API) of Cloud DevOps Nanodegree from Udacity. Based on pre-trained model this repo operationalizes a Python flask app (provided by Udacity).
Scope of the project:
1) Setting up environment 
2) Testing code by linting both locally and by means of CircleCi (badge attached)
3) Improving logging in py.app file
4) Deplyoment of containerized application by Docker and making prediction (in docker_output.txt)
5) Configure Kubernetes and creating Kubernetes cluster
6) Deployment of containerized application by Kubernetes and making prediction (in kubernetes_output.txt)

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

## Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

## Kubernetes Steps

* Setup and Configure Docker locally (docker login)
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl





