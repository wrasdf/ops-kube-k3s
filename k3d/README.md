#### K3d

- Run k3s inside containers for development
- Create new cluster in seconds
- Multiple clusters, multinode cluster
- Runs on Docker (Docker for Desktop)

### Commands

- $ k3d cluster create k3demo --config ./cluster.yaml


### Errors
```
ERRO[0122] Failed Cluster Start: Failed to add one or more agents: Node k3d-k3demo-agent-0 failed to get ready: error waiting for log line `successfully registered node` from node 'k3d-k3demo-agent-0': stopped returning log lines: context deadline exceeded
ERRO[0122] Failed to create cluster >>> Rolling Back
INFO[0122] Deleting cluster 'k3demo'
INFO[0122] Deleting 1 attached volumes...
FATA[0122] Cluster creation FAILED, all changes have been rolled back!
```