- On Terminal, Run the following command:

`kubectl apply -f node-app-deployment.yaml`

- You can Check if the deployment is available or not by:

`kubectl get pods`

- Then, Create the Service

`kubectl apply -f node-app-service.yaml`

- Check by using the following command:

`kubectl get service`

- Run the Service by using following command
  `minikube service <service_name>`

- For our instance, It will be `node-app-service`. So, Run

`minikube service node-app-service`

- Check all the logs in the lens. Download it from this [Link](https://k8slens.dev/)
