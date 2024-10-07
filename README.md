# ada-eks-deploy

# Create cluster

eksctl create cluster --name=ada-cluster-2 --region=us-east-2 --nodegroup-name=ada-nodes --node-type=t2.micro --nodes 4

# Delete cluster

eksctl delete cluster --name=ada-cluster-2 --region=us-east-2

# Get services

kubectl get services

# Get pods

kubectl get pods

# Check pod data

kubectl get pods -o wide

# Forceful delete pod

kubectl delete pod my-pod --force
