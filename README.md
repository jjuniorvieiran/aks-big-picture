# aks-big-picture

- azure cloud shell has kubectl embedded  

## set up apps local 

- `docker container run --name myapp1 -d -p 8081:80 manojnair/myapp:v1`
- `docker container run --name myapp2 -d -p 8082:80 manojnair/myapp:v2`
- `docker container run --name myapp3 -d -p 8083:80 manojnair/myapp:v3`
- `docker container run --name myapp4 -d -p 8084:80 manojnair/myapp:v4`


## set up k8s in azure
- create resource > container > kubernetes


## azure cli command
- `az login`
- `az account show`
- `az configure --defaults group=jj-aks-rg1`
- `az aks get-credentials --name jjaksdemo1` get the credentails and merge our local context
