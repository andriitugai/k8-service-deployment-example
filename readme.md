Check if there are any pods deployed:
$ kubectl get pods
Check if there are other services
$ kubectl get svc

Create pods and services:
$ kubectl create -f voting-app-pod.yaml
$ kubectl create -f votong-app-service.yaml

Check status
$ kubectl get pods, svc

Get vote app's URL:
$ minikube service voting-service --url

$ kubectl create -f redis-pod.yaml
$ kubectl create -f redis-service.yaml

$ kubectl create -f postgres-pod.yaml
$ kubectl create -f postgres-service.yaml

$ kubectl create -f worker-app-pod.yaml

$ kubectl create -f redsult-app-pod.yaml
$ kubectl create -f result-app-service.yaml

Get result app's URL:
$ minikube service result-service --url
