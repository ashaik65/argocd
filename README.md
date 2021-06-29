# argocd
https://github.com/argoproj/argo-cd #use this argocd repo for install argo repo
go to latest stable repo
https://github.com/argoproj/argo-cd/releases/tag/v2.0.4

if you are using in Non-HA repo
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/v2.0.4/manifests/install.yaml

if you are using HA repo
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/v2.0.4/manifests/ha/install.yaml
