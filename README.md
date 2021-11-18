readme
### kubectl apply commands in order
    
    kubectl -- apply -f mysql.yaml
    kubectl -- apply -f mysql-configmap.yaml 
    kubectl -- apply -f mysql-secret.yaml
    kubectl -- apply -f laravel.yaml
    kubectl -- apply -f laravel-configmap.yaml 
    kubectl -- apply -f frontend.yaml
    kubectl -- apply -f ingress.yaml  
    
### kubectl get commands

    kubectl get pod
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all | grep mongodb

### kubectl debugging commands

    kubectl describe pod blog-back-deployment-xxxxxx
    kubectl describe service mysql-service
    kubectl logs blog-front-xxxxxx

### give a URL to external service in minikube

    minikube service blog-front-service