Safaricom Devops Challenge

1, I created a deployment file with the necessary parameters and set the service to listen for the app on port 80
2, created the persistentVolumeClaim config file with necessary parameters and attributes

3, use kubectl apply -f safaricom-statefulset.yaml, safaricom-service.yaml and safaricom-data
4, get details about the set using "kubectl get statefulsets"
5,
6,
7, use this command to scale the number of available replicas of containers "kubectl scale statefulset safaricom-statefulset --replicas=3"
8, use "kubectl get pvc" to get a list of pvc
9, use "kubectl delete "
