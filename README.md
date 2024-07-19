1. Use list to create multiple namespace
2. *build image*: docker  build -t web:v1 Dockerfile
3. *docker registry login*: docker login --username <username>
4. *docker push*: docker tag web:v3 drashti08/wordsmith-web:v3
5. *docker push*: drashti08/wordsmith-web:v3
6. *authenticate minikube with private docker registry*: minikube addons configure registry-creds
7. run deployment and svc as type load balancer and use minikube tunnel command to assign an external ip to svc
8. access the web by hitting external ip and port 80
9. create config-map for backend service