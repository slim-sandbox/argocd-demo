# argocd-demo

# kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d

argocd login localhost:8080 --username admin --password lNmLAH88fZcfiRBi 

kubectl apply -f applications/ws-nginx-hc.yaml -n argocd
