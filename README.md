******************************* kubernetes-mongo-cluster **********************************
Kubernetes MONGO clusterwith Mongo EXPRESS UI: reference by NANA JANASHIA youtube tutorials
Reference youtube link https://www.youtube.com/watch?v=X48VuDVv0do
*********************************** use the master branch *********************************

TO set up this cluster :
1. Need to have Docker desktop running 

Execute this commands:
1. minikuber start --vm-driver=docker
2. minikube dashboard // This will open up the kubernetes UI on your browser

***start up  new CMD ****
1. kubectl apply -f mongo-secret.yaml
2. kubectl apply -f mongo=configmap.yaml
3. kubectl apply -f mongo.yaml
4. kubectl apply -f mongo-express.yaml
5. minikube service mongo-express-service //this will open up the MONGO UI on the browser
