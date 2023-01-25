# Get start

## create a docker image on local
```docker build -t localhost:5000/video-streaming .```        

## Minikube 
```minikube start --container-runtime=docker```      


```minikube dashboard``` follow the links that provided

## Kubectl

create service and deployment ```kubectl create -f deployment.yml```


## See the deployment

```minikube service videostreamingservice```

the links show up

add parameter to the link as `/video` after the link