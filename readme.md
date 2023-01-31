# Subgraphs in Javascript
> ⚠️ This repository is part of the Federation Workshop, a walk-through guide on building and implementing a supergraph. Please refer to [link] to get started. 

## Getting Started
Each subgraph can work in conjunction with other implemented subgraphs in the workshop, as long as there are the three subgraphs serving the three domains (orders, products, and customers).

This repository contains the example subgraphs using Javascript with Apollo Server.


rover subgraph publish jsterner-workshop@current \
 --schema ./schema.graphql \
 --name orders \
 --routing-url fed-workshop-subgraphs-js-production-a948.up.railway.appcd ..


 rover subgraph publish jsterner-workshop@current \
 --schema ./schema.graphql \
 --name customers \
 --routing-url https://subgraph-customers-j3nprurqka-ue.a.run.app

API Key:
 service:jsterner-workshop:aQpsu1VXrPEVLXMkgtxtWQ