kubectl create namespace mysql-server
kubectl create configmap mysql-config --from-file=main-config=my-custom.cnf -n mysql-server