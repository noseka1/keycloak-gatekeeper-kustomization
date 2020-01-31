# Kustomization for Deploying keycloak-gatekeeper on OpenShift

This kustomization deploys [keycloak-gatekeeper](https://github.com/keycloak/keycloak-gatekeeper) on OpenShift.

Edit the keycloak-gatekeeper configuration file [base/conf/config.yml](base/conf/config.yml).

Deploy keycloak-gatekeeper into the current namespace using:

```
$ oc apply --kustomize base
```
