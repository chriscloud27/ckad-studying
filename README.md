# ckad-studying
K8s examples and material for the CKAD exam


## Wordpress Example
This example enhances the code of https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/ by the following:

[x] separation of microservices 'wordpress' und 'db'
[] pods are provisioned in different namespaces and with specific network policies
[] pods are enhanced with Liveness and Readines probes
[] Pods nur auf tainted nodes provisionieren
[x] ConfigMaps for Deployments created
[] PVCs for the DB is created