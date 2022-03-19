# k8s-cron
How to run node app inside kubernetes using CronJob

# Requirements
* Install docker - https://docs.docker.com/get-docker/
* Install kubectl - https://kubernetes.io/docs/tasks/tools/
* Install kind - https://kind.sigs.k8s.io/docs/user/quick-start

# Steps
## Clone code
```sh
$ git@github.com:tiagovbarreto/k8s-cron.git
```

## Create cluster
```sh
$ Kind create cluster --name my-cluster
```

## Deploy k8s infra
```sh
$ kubectl apply -f infra/k8s/*
```

## Verify infra deploy
```sh
$ kubectl get all
```
