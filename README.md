# tekton各组件部署yaml
## 部署pipeline
```
kubectl apply -f tekton-pipeline-release-v0-13-2.yaml
```
## 部署dashboard
```
kubectl apply -f tekton-dashboard-release-latest.yaml
```
## 部署trigger
```
kubectl apply -f tekton-trigger-release.yaml
```
## 关注微信公众号“云原生手记”，学习更多tekton知识点以及使用案例
