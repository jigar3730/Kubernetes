# Work in progress will update with commands and notes as i go 
Simple list of commands to test out github codespace Minikube installation 
### Commands to run
- minikube status
- minikube start
- kubectl create deployment nginx --image=nginx:1.10.0 --replicas=3	
- kubectl get pods	
- kubectl expose deployment nginx --port 80 --type LoadBalancer	
- kubectl get services	
- minikube service nginx --url	
- curl http://192.168.49.2:31967  (Update with url returned from above command )	
- minikube dashboard	
- kubectl scale deployment nginx --replicas=10	


#### minikube status  
check the status of minikube see if its running if not start it

#### minikube start
Starts minikube 

#### kubectl create deployment nginx --image=nginx:1.10.0 --replicas=3
Starts simple nginx image and scales it to 3 pods 

#### kubectl get pods
lists all running pods



#### kubectl expose deployment nginx --port 80 --type LoadBalancer
expose deployment and create a service 

#### kubectl get services
Get list of services 
 
#### minikube service nginx --url
find the service URL and check if the page loads 

#### curl http://XXX.XXX.XX.XX:XXXX  (Update with url returned from above command )  
 

#### minikube dashboard
Start minikube dashboard and review the deployments – feel free to explore dashboard

#### kubectl scale deployment nginx --replicas=10
issue scale deployment to increase replicas to 10 and review the dashboard


 
