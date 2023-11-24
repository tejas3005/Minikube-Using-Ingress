# Minikube-Ingress-Demonstartion

Welcome to the Minikube Ingress Demonstration repository! This project provides a simple and hands-on demonstration of setting up and using Ingress with Minikube, allowing you to easily expose and access your Kubernetes services.

Step 1:  Setting up Environment on github codespace

![image](https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/baa96a66-071b-4b77-9cae-992404c3b43b)

![image](https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/e7055354-ce2a-4f8f-ba04-44e90cdfb8f9)

![image](https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/e455cf85-5e3a-423e-b280-d66425f1d0ce)

![image](https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/868b4d65-ac54-4245-b223-a45ef35204f1)

![image](https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/47b2541a-b9b9-4da9-8367-8eb2c13b4a6f)



![image](https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/480d076a-3ea0-4bec-9ee3-3b3a330ba9c1)

Step 2:
  git clone https://github.com/tejas3005/Minikube-Using-Ingress.git

Step 3:
  ansible-playbook deploy-minikube.yaml

step 4: 
  minikube service hello-kubernetes-first --url

  THE OUTOUT SHOULD BE:

<img width="626" alt="image" src="https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/b84bbc69-b7bc-473c-966a-c2565b1441c0">


step 5:
  curl http://<minikubeip>:portnumber

  THE OUTPUT SHOULD BE:

 <img width="574" alt="image" src="https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/0c61b9a0-36f3-4aae-82d5-6b32f47f47e2">

 NOTE :

1. to check Minikube status use:
  minikube status

THE OUTPUT SHOULD BE:

<img width="551" alt="image" src="https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/4f44d25d-ea5d-4adb-a3e1-ce93f86fe1e8">

2. t0 check status of all running pods, deployments and services use:
  kubectl get pods,services --all-namespaces

THE OUTPUT SHOULD BE:

<img width="829" alt="image" src="https://github.com/tejas3005/Minikube-Using-Ingress/assets/48887643/3f8e4833-f09e-417e-b7aa-86737ed78aee">


   

 


