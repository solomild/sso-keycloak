```ssh
    minikube start
    kubectl create -f keycloak.yaml
    kubectl apply -f keycloak.yaml
    kubectl logs -f pod/keycloak-5ff4bd964b-dvn2h
    kubectl get all
    kubectl port-forward service/keycloak 8080:8080
    minikube delete --all
```