# SWARM

Swarm playground is a script that creates a single consul node, with a signle swarm master node and an arbritrary number of docker nodes.

```bash
$ ./swarm bootstrap node-01 node-02
$ eval "$(./swarm env)"
$ docker info
```
