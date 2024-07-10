# quackers-bank-flux
```
kubectl create secret generic -n cluster-config csi-driver-config \
  --from-literal=USER_ASSIGNED_CLIENT_ID= \
  --from-literal=IDENTITY_TENANT= \
  --from-literal=KEYVAULT_NAME=
```