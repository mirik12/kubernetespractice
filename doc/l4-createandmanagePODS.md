 1093* minikube start
 1094* kubectl get nodes
 1095* kubectl get pods
 1096* kubectl run hello --generator=run-pod/v1 --image=mirik12mirik/k8sphp:latest --port=80
 1097* kubectl create hello --image=mirik12mirik/k8sphp:latest --port=80\n
 1098* kubectl create deployment hello --image=mirik12mirik/k8sphp:latest --port=80\n\n
 1099* kubectl create pod hello --image=mirik12mirik/k8sphp:latest --port=80\n\n
 1100* kubectl delete deployment hello\n
 1101* kubectl create pod hello --image=mirik12mirik/k8sphp:latest --port=80\n
 1102* kubectl run hello --image=mirik12mirik/k8sphp:latest --port=80 --generator=run-pod/v1\n
 1103* kubectl run hello --image=mirik12mirik/k8sphp:latest --port=80\n
 1104* kubectl get pods
 1105* kubectl delete pods hello
 1106* kubectl get pods
 1107* kubectl run hello --image=mirik12mirik/k8sphp:latest --port=80\n
 1108* kubectl get pods
 1109* kubectl describe pods hello
 1110* kubectl execute hello date
 1111* kubectl exec hello date
 1112* kubectl exec hello sh
 1113* kubectl exec hello -- sh\n
 1114* kubectl exec -it hello -- sh\n
 1115* kubectl logs hello
 1116* kubectl get podes
 1117* kubectl get pods
 1118* kubectl port-forward hello 7788:80
 1119* kubectl get pods
 1120* kubectl delete pods hello
 1121* kubectl get pods
 1122* ll
 1123* cd pods
 1124* ll
 1125* kubectl apply -f pod-myweb-ver1.yaml
 1126* kubectl get pods
 1127* kubectl describe pods pod-myweb-ver1.yaml
 1128* kubectl describe pods my-web  
 1129* kubectl delete
 1130* kubectl delete -f pod-myweb-ver1.yaml
 1131* kubectl get pods
 1132* kubectl apply -f pod-myweb-ver1.yaml
 1133* kubectl get pods
 1134* kubectl describe pods my-web  
 1135* kubectl port-forward my-web 8888:80
 1136* kubectl apply -f pod-myweb-ver1.yaml
 1137* kubectl get pods
 1138* kubectl describe pods my-web  
 1139* kubectl port-forward my-web 8888:80
 1140* kubectl apply -f pod-myweb-ver1.yaml
 1141* kubectl delete -f pod-myweb-ver1.yaml
 1142* kubectl apply -f pod-myweb-ver1.yaml
 1143* kubectl describe pods my-web  
 1144* kubectl delete -f pod-myweb-ver1.yaml
 1145* kubectl apply -f pod-myweb-ver2.yaml
 1146* kubectl describe pods my-web  
 1147* kubectl get pods
 1148* ll
 1149* kubectl apply -f pod-myapp.yaml
 1150* kubectl get pods
 1151* kubectl describe pods my-app
 1152* kubectl get pods
 1153* kubectl port-forward my-app 5555:80
 1154* kubectl port-forward my-app 5555:8080
 1155* kubectl get pods
 1156* kubectl describe pods my-app
 1157* kubectl get nodes