# argo-workflows

#### Descargamos el cliente

curl -sLO https://github.com/argoproj/argo-workflows/releases/download/v3.1.12/argo-linux-amd64.gz


#### Web UI
kubectl port-forward deployment/argo-workflows-server 2746:2746
http://localhost:2746


### Para levantar el server sin autenticacion:
argo server --auth-mode server

