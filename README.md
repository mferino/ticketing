## Tickets?

A stub hub sort of site that uses microservices

### Steps to get things running locally

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

update hosts file which on mac/linux can be found at `/etc/hosts` and on windows `C:\Windows\System3d\Drivers\etc\hosts` (if you are using WSL be sure to update the host file in windows, editing the /etc/hosts file inside WSL doesn't do anything)

add for local development

```sh
127.0.0.1 ticketing.dev
```
