
#### Screnshoots
<table>
     <td><a href="#"><img src="https://user-images.githubusercontent.com/34090058/80102977-359ad580-857c-11ea-8cd0-c723d711f444.png" width="400"></a></td>
</table>

#### How to running deployment.yaml
```
kubectl apply -f deployment.yaml
```
#### Listing deployment, service, replicaset, pod
```
kubectl get all
```
#### Pod Description
```
kubectl describe po helloworld
```

#### to open shell in Pod
```
kubectl -it  exec helloworld -- sh
```
#### Test to Browse
**minikube runnig for Local**
get minikube ip:
```
minikube ip
```
and
runnig browse
minikubeip:30080
**minikube running for server(aws/ec2 - gcloud - digitalocean)**
publicip:30080

