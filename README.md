# eth2-node
Docker Compose setup for setting up an ETH 2.0 validator node

Usage:
```
# Run as daemon
docker-compose up -d

# Updates
docker-compose pull
```

If you're looking for how to install Docker Compose:
https://docs.docker.com/engine/install/ubuntu/

## geth (ETH 1.0 node)
Running a geth node (no RPC) on stable branch

Reference:
* https://hub.docker.com/r/ethereum/client-go/
  * https://hub.docker.com/r/ethereum/client-go/tags?page=1&ordering=last_updated
* https://www.freecodecamp.org/news/how-to-run-geth-from-a-docker-container-b6d30620ca74/
* https://github.com/islishude/geth-docker/ 
