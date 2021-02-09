```zsh
$ helm install minecraft -f values.yaml itzg/minecraft

$ k expose deployment minecraft-minecraft --type=LoadBalancer --name=mc-expose
```