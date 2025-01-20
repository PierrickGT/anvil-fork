# Anvil fork for local development
### Docker compose for run fork chain to local chain with block explorer

## Setup environment

```bash
# create .env and require to fill your environment in the .env file
cp example.env .env
```
                              
## Run fork chain

```
docker compose up -d
```
- Anvil RPC: http://127.0.0.1:8545
- Otter scan: http://127.0.0.1:8000

## Run block scout
```bash
cd ./blockscout
docker compose up -d
```

- Blockscout: http://127.0.0.1:3000
