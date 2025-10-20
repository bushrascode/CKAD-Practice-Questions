**Questions and Answers**

1. List all the namespaces in the cluster
        kubectlt get ns -A
2. List all the pods in all namespaces
        kubectl get pods -A
3. List all the pods in a particular namespace
        kubectl get pods --namespace=kube-system
4. List all the services in the particular namespace 
        kubectl svc --namespace=kube-system 
5. List all the pods showing name and namespace with a json path expression
        kubectl get pods -o=jsonpath="{.items[*]['metadata.name', 'metadata.namespace']}"
