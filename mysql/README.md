# 创建
kubectl delete -f mysql-config.yaml -f mysql-secret.yaml -f mysql-pv-claim.yaml -f mysql-pv.yaml -f mysql-deployment.yaml -f mysql-service.yaml


# 删除
kubectl delete -f mysql-config.yaml -f mysql-secret.yaml -f mysql-pv-claim.yaml -f mysql-pv.yaml -f mysql-deployment.yaml -f mysql-service.yaml