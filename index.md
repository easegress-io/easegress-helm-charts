# Easegress Helm Repository

![Easegress](./img/easegress.svg)

## Add the Easegress Helm repository

```bash
helm repo add easegress https://megaease.github.io/easegress-helm-charts
```

## Install Easegress

```bash
helm install easegress easegress/easegress
```

## Install Ingress Controller

```bash
helm install ingress-easegress easegress/easegress-ingress-controller
```
