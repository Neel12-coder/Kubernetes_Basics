# Kubernetes_Basics Commands

kubectl get pods
kubectl create -f <file-name>.yaml
kubectl describe pod <name>
kubectl rollout status deployment/<deployment-nmae>
kubectl rollout history deployment/<deployment-name>
kubectl rollout undo deployment/<deployment-name>
kubectl edit replicaset <replicaset-name>
kubectl scale --replicas = 6 replicaset <name>.yaml
kubectl get svc
kubectl set image deployment/<deployment-name> <container-name>=<image-name>