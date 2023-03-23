# 2a
kubectl run pod-nginx --image=nginx

# 2b
kubectl port-forward pod-nginx 80:8080

# 3a
kubectl apply -f docker-compose-mysql.yml
kubectl apply -f docker-compose-php.yml