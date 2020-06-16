# Welcome to rainmanh's Github Helm Repository

This is a Repository for Kubernetes Helm Charts

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

# Helm Menu

At the moment just got a minikube jenkins master/slave setup

- k8s-jenkins-minikube

## k8s-jenkins-minikube

Usage: 

1. Add repo
```
helm repo add k8s-jenkins-minikube https://rainmanh.github.io/k8s-jenkins-minikube
```

2. install defaults
```
helm install jenkins k8s-jenkins-minikube/k8s-jenkins-minikube
```

If you need to check on the versions :

```
helm search  repo  k8s-jenkins-minikube
```