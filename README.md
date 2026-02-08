# learn-kubernetes

#default namespace
kubectl get pods

#create nginx pod
kubectl run nginx --image nginx

#To know about a pod
kubectl describe pod <podname>

#to delete a pod
kubectl delete pod webapp