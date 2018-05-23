# wordpress_afs_pv

kubectl create -f 1_azure-secret.yaml

kubectl create -f 2_mysql-secret.yaml

kubectl create -f 3_mysql-pv.yaml

kubectl create -f 3_storageclass.yaml

kubectl create -f 4_mysql-pvc.yaml

kubectl create -f 5_mysql-deployment.yaml

kubectl create -f 6_mysql-svc.yaml

kubectl create -f 7_wordpress-pv.yaml

kubectl create -f 8_wordpress-pvc.yaml

kubectl create -f 9_wordpress-deployment.yaml

kubectl create -f 10_wordpress-svc.yaml