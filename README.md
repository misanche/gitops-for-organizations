# Install
1. Get the bootstrap chart dependencies:
    ```helm dep up base/components/bootstrap```
2. Install the bootstrap helm char
   ```helm upgrade --install bootstrap-cluster-ops -f conf/bootstrap/conf.yaml base/components/bootstrap --create-namespace --namespace cluster-ops-bootstrap```
