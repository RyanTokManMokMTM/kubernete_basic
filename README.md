## kubernetes playground
Items:
* Node - minikube
* Pod
* Replication
* ReplicationSet - Deployment(Scale/Update without downtime/RollOut/RollBack)
* Service
* Secret - FromFile/FromYaml/From Iiteral
* AWS Deploy
* ConfigMap 
** ConfigMap - for config data. eg:redis config file, server config file etc...
** Secret - for any secret data - base64 encrypt. eg: password, key etc...
* Ingress - a component used to direct the request to the corresponding service
* *can use as load balancer*
** For example: 127.0.0.1 /test -> service abc:8080
** For example: 127.0.0.2 /test -> service def:8080
