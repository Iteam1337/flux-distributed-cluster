# Distributed cluster lab

## Cluster setup

Please refer to the cluster setup guide on Outline.

When installing k3s on the controller node, make sure you configure the flannel backend to use wireguard.

```shell
./k3s --flannel-backend=wireguard-native
```
