# ada-eks-deploy

# Create cluster

eksctl create cluster --name=ada-cluster-2 --region=us-east-2 --nodegroup-name=ada-nodes --node-type=t2.micro --nodes 2

# Delete cluster

eksctl delete cluster --name=ada-cluster-2 --region=us-east-2
