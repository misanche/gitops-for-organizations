# Install
1. Get the bootstrap chart dependencies:
    ```helm dep up base/components/bootstrap```
2. Install the bootstrap helm char
   ```helm upgrade --install bootstrap-cluster-ops -f conf/acm/conf.yaml base/components/bootstrap --create-namespace --namespace cluster-ops-bootstrap```
3. Apply the first application.
   ```oc apply -f clusters/acm/applications/bootstrap-app.yaml```