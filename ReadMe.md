### build image and push

- docker build -t ayorich/query .
- docker push ayorich/query

### create pods and services

- kubectl apply -f .
- kubectl get services
- kubectl get pods

### restart deployments

- kubectl get deployments
- kubectl rollout restart deployment event-bus-depl

### logs

- kubectl get pods
- kubectl logs comments-depl-79cbbdc56b-gqh6z

### checking what is running on a port (windows)

- netstat -anb
