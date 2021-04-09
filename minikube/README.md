# Descomplicando o Kubernetes

## Installing and configuring Minikube

### [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)

- Installed and configured the kubectl:

```shell
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl
kubectl version --client
kubectl --help
```

### [Minikube](https://minikube.sigs.k8s.io/docs/start/)

- Installed minikube:

```shell
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube
minikube version
minikube --help
rm minikube-linux-amd64
```
