Documentation

Create

`kubectl create -f deployment.definition.yml`

Get

`kubectl get deployments`

Update

`kubectl apply -f deployment-definition.yml`

`kubectl set image deployment/myapp-deployment nginx=nginx:1.9.1`

Status

`Kubectl rollout status deployment/myapp-deployment`

`kubectl rollout history deployment/myapp-deployment`

Rollback

`kubectl rollout undo deployment/myapp-development`
