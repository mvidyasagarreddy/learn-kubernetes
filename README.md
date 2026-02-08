# learn-kubernetes

#default namespace
kubectl get pods

#create nginx pod
kubectl run nginx --image nginx

#To know about a pod
kubectl describe pod <podname>

#to delete a pod
kubectl delete pod webapp

kubectl create -f replicaset-definition.yaml

kubectl get replicaset

kubectl delete replicaset myapp-repicaset <This also deletes all underlying pods>

kubectl replace -f replicaset-definition.yaml

kubectl scale -replicas=6 -f replicaset-definition.yaml