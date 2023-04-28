## Work in progress will update with commands and notes as i go 
- Create docker container with node js
- run local container 
- Deploy workload to kubernetes


minikube start --vm-driver=docker --cni=calico
minikube status
minikube get all
kubectl get all
minikube dashboard
kubectl get all
kubectl create deploy myapp --image=nginx --replica=2
kubectl create deploy myapp --image=nginx --replicas=2
kubectl get all
source <(kubectl completion bash)
kubectl get a;;
kubectl get all
kubectl create deploy myapp --image-nginx --replicas=3 --dry-run=client -o yaml > myapp.yaml
kubectl create deploy myapp --image=nginx --replicas=3 --dry-run=client -o yaml > myapp.yaml
ls
cat myapp.yaml

kubectl get all
kubectl apply -f myapp.yaml
kubectl get all
kubectl create deploy myapp --image=nginx --replicas=2 --dry-run=client -o yaml > myapp.yaml
kubectl get all
kubectl apply -f myapp.yaml
kubectl get all
kubectl create deployment my-dep --image=busybox
kubectl get all
clear
kubectl get all
kubectl delete deploy my-dep
kubectl delete de\loy my-dep
kubectl delete deploy my-dep
kubectl get all
   39  kubectl delete deploy firstnginx 
   40  kubectl
   41  kubectl get all
   42  kubectl delete deploy myapp 
   43  history
   44  history > commands.txt
   45  ls
   46  ls -la
   47  cat commands.txt 
   48  kubectl get all
   49  kubectl create deployment my-dep --image=busybox
   50  kubectl get all
   51  exit
   52  minikube
   53  podman
   54  docker
   55  git clone https://github.com/sandervanvugt/kubernetes
   56  sudo apt install git
   57  git clone https://github.com/sandervanvugt/kubernetes
   58  cd kubernetes/
   59  ls
   60  ./minikube-docker-setup.sh
   61  sudo reboot
   62  kubectl
   63  kubectl get all
   64  minikube
   65  history
   66  minikube start -h
   67  minikube start -h |less
   68  minikube start -h | more
   69  kubectl get a;;
   70  kubectl get all
   71  kubectl delete deployment my-dep
   72  kubectl get all
   73  kubectl create deployment --image=busybox --sleep=3600
   74  kubectl create deployment --image=busybox -- sleep 3600
   75  kubectl create deployment my-dep --image=busybox -- sleep 3600
   76  kubectl get all
   77  kubectl create ns secret
   78  kubectl create deploy secret --image=nginx -n secret
   79  kubectl get all
   80  kubectl get all -n secret
   81  kubectl get al-A
   82  kubectl get all -A
   83  clear
   84  kubectl config view 
   85  history
   86  minikube start --vm-driver=docker --cni=calico
   87  ls -la
   88  cd .kube/
   89  ls
   90  nano config 

