
## run


kubectl create deployment echo-server --image=ealen/echo-server
kubectl expose deployment echo-server --port 80 --target-port 80 --type LoadBalacer