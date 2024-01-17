## ETH
This repository contains instructions for setting up the SSV_NODE environment.

### Clone the repository:
```
git clone https://github.com/goooodnes/ETH_hol.git
cd ETH_hol
```

Alternative chekpoint if standart checkpoint is blocked
```
lighthouse:
  --checkpoint-sync-url=https://checkpoint-sync.holesky.ethpandaops.io/
```

```
docker-compose up -d
docker-compose logs --tail 100 -f
```




