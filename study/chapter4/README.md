# 第4章 API リソースと kubectl

## Sample Pod
```bash
kubectl apply -f sample-pod.yml
```
## Sample Deployment
DeploymentでのPod適用を実施。Deploymentをrolloutすることで再起動可能。Podに対してのrolloutはサポートされていない。
```bash
kubectl apply -f sample-deployment.yml
```
## Sample Multi Resource Manifest
複数のリソースを同時定義する。
```bash
kubectl apply -f sample-multi-resource-manifest.yml
```
