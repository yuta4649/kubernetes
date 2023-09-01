# Kubenetes

## 進捗
Kubernetes完全ガイド <br>
~112ページまで
## ACR Pull Secret 作成
```bash
kubectl create secret docker-registry acr-secret \
    --namespace default \
    --docker-server=acryutatestregistry.azurecr.io \
    --docker-username=acryutatestregistry \
    --docker-password=xAUSR0+SF2+UbjsIsm5uSjcHHmRJ+/Ml5XkELU6gwO+ACRBe5DTr
```
## ServiceAccount 作成
```bash
kubectl apply -f sa/service-account.yml
kubectl apply -f sa/role-edit.yml
```
