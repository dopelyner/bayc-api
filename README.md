# Bored Ape Yacht Club subgraph

![Bored Ape Yach Club Subgraph](bayc.png)

```
graph init --contract-name <CONTRACT_NAME> \
--index-events \
--product hosted-studio \
--from-contract <Contract_ADDRESS>
```
```
graph auth --product hosted-service <ACCESS_TOKEN>
```
```
graph deploy --product hosted-service <username/subgraph-name>
```

Deployed to https://thegraph.com/explorer/subgraph/dopelyner/bayc-api 

Queries (HTTP): https://api.thegraph.com/subgraphs/name/dopelyner/bayc-api

Graph Explorer: https://thegraph.com/hosted-service/subgraph/dopelyner/bayc-api