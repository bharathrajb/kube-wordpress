# kube-wordpress
Deploy Kubernetes Cluster on any gcloud ( 90 days Free trail for demo) or can be paid 
https://console.cloud.google.com/ register with ne user adn all detail and login

Please refer Kube-doc and automate deployment pdf files based


Download the attached and deploy as below mentioned commands

### kubectl apply commands in order
    
    kubectl apply -f mongo-secret.yaml
    kubectl apply -f mongo.yaml
    kubectl apply -f mongo-configmap.yaml 
    kubectl apply -f mongo-express.yaml

### kubectl get commands

    kubectl get pod
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all | grep mongodb

### kubectl debugging commands

    kubectl describe pod mongodb-deployment-xxxxxx
    kubectl describe service mongodb-service
    kubectl logs mongo-express-xxxxxx

