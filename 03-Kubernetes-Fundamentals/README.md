# Kubernetes Fundamentals
- For Kubernetes Fundamentals github repository, please click on below link
- https://github.com/stacksimplify/kubernetes-fundamentals


# Kubernetes - Essential Commands
- The below are the list of essential commands we are in need 

|     Commands                 |    Description                                  |
| ------------------------------- | --------------------------------------------- |
| kubectl get all -n 'kube-system' | List all objects in 'kube-system' 'Namespace' |
| kubectl get all --all-namespaces | List all objects in all 'Namespaces' |
| kubectl api-resources -o wide | Finding API version for objects |
| kubectl create ns 'dev1' | Create 'dev1' 'Namespace' |
| kubectl delete ns 'dev1' | Delete all objects in 'dev1' 'Namespace' |
| kubectl resources-capacity | Show resources capacity |
| kubectl cordon 'Node' | Mark a 'Node' as invalid |
| kubectl logs -f 'Podname' -n 'Nameservice' | Get logs of a pod |
| kubectl edit deployment 'Deploy'  --namespace 'Namespace' | Edit one deploy in specific 'Namespace' |
| kubectl apply -f nginx-deploy.yaml | Create a deployment in the default namespace. |
