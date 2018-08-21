### Install Helm

Checkout docs at https://docs.helm.sh/install/

### Deploy role

```
kubectl apply -f https://raw.githubusercontent.com/gsviec/kubernetes-training/master/helm/rbac-config.yaml
helm init --service-account tiller --upgrade
kubectl create namespace tiller-world

```
