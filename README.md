[![Build Status](https://app.travis-ci.com/trev-dev0/prod-flask.svg?branch=main)](https://app.travis-ci.com/trev-dev0/prod-flask)
# prod-flask

### about
A hello world app that showcases a scalable flask app with uWSGI to interface with flask and nginx for load balancing and scalability.


### run with docker-compose
```shell
docker-compose up -d --build
# go to localhost:8000
```

### run in a kubernetes cluster (minikube)
```shell
cd kubernetes
kubectl apply -f .
minikube flask-nginx-svc # tunnel
```