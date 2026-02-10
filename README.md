"# lab-snippet" 
"# lab-snippet" 




## create deployment 
install using kubectl apply -f nginx-deploy.yaml



## create service 
install using kubectl apply -f nginx-nodeport-svc.yaml 




## check 
kubectl get pods -o wide 

kubectl get service