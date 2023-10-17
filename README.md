# collectors-channel-k8s

## Getting started
  - Replace the environment variables (started with _$_) with the desired values before using the apps.
    - Recommended the usage of the [direnv](https://direnv.net/) plugin to automate this process.

## Dependencies
  - [Istio](https://istio.io/)
  - [nfs-subdir-external-provisioner](https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner)
  - [sealed-secrets](https://github.com/bitnami-labs/sealed-secrets)
  - Istio Gateway available on `istio-custom/default-gateway`
    - [Example](https://github.com/pjosalgado/homelab-templates/blob/main/Kubernetes/Infraestructure/Istio/gateways.yaml)
