# minikube
DevOps + Kubernetes + Elasticsearch + Kibana + servidor APM


# Arquitetura Kubernetes 

Necessario a instalação do kubectl 

curl -LO "https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl"

chmod +x ./kubectl

sudo mv ./kubectl /usr/local/bin/kubectl

kubectl version --client

Link: https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl-binary-with-curl-on-linux


Necessario a instalação do minikube

curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64

 sudo install minikube-linux-amd64 /usr/local/bin/minikube
 
 minikube start
 
 Link: https://minikube.sigs.k8s.io/docs/start/

### Setup Elastic stack on Kubernetes

Configuração necessária para executar o servidor Elasticsearch + Kibana + Elastic APM e um aplicativo Node.js no Kubernetes
