history

1238* kubectl get nodes
 1239* kubectl get podes
 1240* history
 1241* kubectl get pods
 1242* kubectl get deploy
 1243* kubectl create deployment mirik-deployment image mirik12mirik/k8sphp:latest
 1244* kubectl create deployment mirik-deployment --image mirik12mirik/k8sphp:latest
 1245* kubectl get pods
 1246* kubectl get deploy
 1247* kubectl describe mirik-deployment-6fcc995c94-4px4c 
 1248* kubectl describe pods mirik-deployment-6fcc995c94-4px4c 
 1249* kubect get deploy
 1250* kubectl get deploy
 1251* kubectl describe deployments mirik-deployment 
 1252* kubectl get pods
 1253* kubectl scale deployment mirik-deployment --replicas=4
 1254* kubectl get pods
 1255* kubectl get deploy
 1256* alias k=kubectl
 1257* k get rs
 1258* k get pods
 1259* k delete pods mirik-deployment-6fcc995c94-4px4c 
 1260* k get pods
 1261* k autoscale deployment mirik-deployment --min=4 --max=6 --cpu-percent=80
 1262* k get pods
 1263* k get deploy
 1264* k get hpa
 1265* k rollout history deployment/mirik-deployment
 1266* k rollout status deployment/mirik-deployment
 1267* k describe deployment mirik-deployment
 1268* k set image deployment/mirik-deployment k8sphp=mirik12/k8sphp:version1 --record
 1269* k rollout status deployment/mirik-deployment
 1270* k rollout history deployment/mirik-deployment
 1271* k set image deployment/mirik-deployment k8sphp=mirik12/k8sphp:version2 --record
 1272* k rollout status deployment/mirik-deployment
 1273* k rollout history deployment/mirik-deployment
 1274* k rollout undo deployment/mirik-deployment
 1275* k rollout status deployment/mirik-deployment
 1276* k rollout history deployment/mirik-deployment
 1277* k set image deployment/mirik-deployment k8sphp=mirik12/k8sphp:latest --record
 1278* k rollout history deployment/mirik-deployment
 1279* k rollout undo deployment/mirik-deployment --to-revision=4
 1280* k rollout status deployment/mirik-deployment
 1281* k describe deployment mirik-deployment
 1282* k rollout restart deployment/mirik-deployment
 1283* k rollout status deployment/mirik-deployment
 1284* cd les9-Deployments
 1285* k apply -f deployment-1-simple.yaml
 1286* k apply -f deployment1-simple.yaml
 1287* cd D
 1288* cd Deployments
 1289* k apply -f deployment1-simple.yaml
 1290* k get deploy
 1291* k apply -f deployment1-simple.yaml
 1292* k get deploy
 1293* k apply -f deployment2-simple.yaml
 1294* k get deploy
 1295* k get pods
 1296* k port-forward my-web-deployment-replicas-56799f4784-8zmm7 6789:80
 1297* k get pods
 1298* kubectl describe pod my-web-deployment-69df4495f6-9thwv  
 1299* k get pods
 1300* docker images
 1301* k get pods
 1302* k delete pods my-web-deployment-replicas-56799f4784-nz75x my-web-deployment-replicas-56799f4784-gr4l2 my-web-deployment-replicas-56799f4784-8zmm7 my-web-deployment-69df4495f6-9thwv   
 1303* k get pods
 1304* k apply -f deployment2-simple.yaml
 1305* k get pods
 1306* k get deploy
 1307* k apply -f deployment2-simple.yaml
 1308* k get deploy
 1309* docker images mirik12/k8sphp\n
 1310* docker images\n
 1311* docker build -t mirik12/k8sphp:version1 .\n
 1312* cd ..
 1313* docker build -t mirik12/k8sphp:version1 .\n
 1314* cd kubernetes
 1315* docker build -t mirik12/k8sphp:version1 .\n
 1316* cd ..
 1317* cd Deployments
 1318* k get pods
 1319* k apply -f deployment2-simple.yaml
 1320* k get pods
 1321* docker pull mirik12/k8sphp:version1
 1322* cd ..
 1323* cd kubernetes
 1324* docker pull mirik12/k8sphp:version1
 1325* docker images
 1326* cd ..
 1327* cd Deployments
 1328* k apply -f deployment2-simple.yaml
 1329* k get pods
 1330* k get deploy
 1331* k delete deploy my-web-deployment-replicas   
 1332* k get deploy
 1333* k apply -f deployment2-simple.yaml
 1334* k get deploy
 1335* docker pull mirik12mirik/k8sphp:version1
 1336* cd ..
 1337* cd kubernetes
 1338* docker pull mirik12mirik/k8sphp:version1
 1339* k get deploy
 1340* cd ..
 1341* cd Deployments
 1342* k get pods
 1343* k delete pods my-web-deployment-replicas-cc65b8b76-m75f8 
 1344* k get pods
 1345* k get deploy
 1346* k delete deploy my-web-deployment-replicas
 1347* k get deploy
 1348* docker image
 1349* docker images
 1350* ll
 1351* k apply -f deployment3-autoscaling.yaml
 1352* kubectl apply -f https://raw.githubusercontent.com/kubernetes/autoscaler/master/vertical-pod-autoscaler/vertical-pod-autoscaler-crd.yaml\n
 1353* k get deploy
 1354* k apply -f deployment3-autoscaling.yaml
 1355* kubectl apply -f https://raw.githubusercontent.com/kubernetes/autoscaler/master/vertical-pod-autoscaler/hack/vpa-updater/deploy/vpa-autoscaling.k8s.io.yaml\n
 1356* kubectl apply -f https://github.com/kubernetes/autoscaler/releases/latest/download/vertical-pod-autoscaler.yaml\n
 1357* k get deploy
 1358* k delete deploy my-web-deployment-autoscaling my-web-deployment mirik-deployment  
 1359* k get deploy
 1360* k get pods