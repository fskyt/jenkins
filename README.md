# Deploy Jenkins to Kubernetes


1) Create a namespace

	```kubectl apply -f jenkins-namespace.yaml```

2) Install helm chart

	```helm install jenkins -f helm/values.yaml jenkins/jenkins --namespace jenkins```
