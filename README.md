# minikube
DevOps + Kubernetes + Elasticsearch + Kibana + APM


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

### verificar se kubectl se comunica corretamente

kubectl cluster-info

Kubernetes master is running at https://192.168.99.101:8443
KubeDNS is running at https://192.168.99.101:8443/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy



