# Deploying Microservices Application on Google Cloud Platform using Google Kubernetes Engine
Create the Account on GCP.
Then search for Kubernetes Cluster.
Click on Create Cluster.
Give the name - voting-app
Click create
Now its launched
Click in Activate Cloud Shell, it will give you terminal
Click in Connect
It will show the command run it on cloud shell
kubectl get nodes
kubectl get pods
kubectl get services
Use git clone to bring the yml files to your system from github(arpita-hub)
cd DeployonKubernetes/
kubectl create -f voting-app-pod.yml
Similarly run the same commands with other yml files
Check all the pods and services be in running state.
You will assigned the internal and external ip.
Using external ip to run you application on the browser 

