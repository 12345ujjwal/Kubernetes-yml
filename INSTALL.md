chmod +x setup.sh
./setup.sh
exit

# Reconnect to the server

docker --version
kind version
kubectl version --client

kind create cluster --name my-cluster
kubectl get nodes
