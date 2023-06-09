Safaricom Devops Challenge

1, I created a deployment file with the necessary parameters and set the service to listen for the app on port 80
2, created the persistentVolumeClaim config file with necessary parameters and attributes

3, use kubectl create -f safaricom-statefulset.yaml, safaricom-service.yaml and safaricom-data
4, get details about the set using "kubectl get statefulset safaricom-nginx-sts" but I don't know how to save it in json file
5, tail the logs using kubectl logs -f -l app=safaricom-nginx-app -n default
6,
7, use this command to scale the number of available replicas of containers "kubectl scale statefulset safaricom-nginx-sts --replicas=3"
8, use "kubectl get pvc" to get a list of pvc
9, use "kubectl delete --force pod safaricom-nginx-sts-0 safaricom-nginx-sts-1 safaricom-nginx-sts-2"
