## Tickets?

A stub hub sort of site that uses microservices

### Installation steps

*Prerequisites*

make sure you have ingress-nginx installed (find instructions [here](https://kubernetes.github.io/ingress-nginx/deploy/))

```sh
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.8.2/deploy/static/provider/cloud/deploy.yaml
```


get things running by installing and running skaffold from root dir (find install instructions [here](https://skaffold.dev/docs/install/))

```sh
# from root directory
skaffold dev
```

