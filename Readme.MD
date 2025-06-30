$git clone https://github.com/Lingaiahthammisetti/9.8.k8s-Helm-Nginx.git
$cd 9.8.k8s-Helm-Nginx
$ls -l

helm install nginx .
helm upgrade nginx .

helm status nginx
helm list
helm history nginx
helm uninstall nginx



# Note: we can access application using Load Balanncer, but it takes some time to load expense application.

a6e42898bef734110ae2c99386b5296a-292488674.us-east-1.elb.amazonaws.com