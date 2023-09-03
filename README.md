# Install-Argocd-using-helm-chart
```
helm repo add argo https://argoproj.github.io/argo-helm
```
```
helm repo update
```
```
helm upgrade --install my-argo-cd argo/argo-cd -f values.yaml -n argocd --create-namespace
```
