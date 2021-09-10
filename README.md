# nginx-test-kubernets
The nginx application deployment in kubernets.

## Prerequisites:-

Deploy ingress-nginx using the below command
`kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.43.0/deploy/static/provider/cloud/deploy.yaml`
Verify ingress-controller is started successfully using the below command
`kubectl get pods -n ingress-nginx`
