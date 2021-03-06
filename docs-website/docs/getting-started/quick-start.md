---
id: quick-start
sidebar_label: 'Quick Start'
title: 'Quick Start'
---
TL;DR? The quickest way to launch GraphQL Portal (with Gateway and Dashboard) locally, is to use our [Docker Compose file](https://github.com:graphql-portal/graphql-portal-docker):
```shell
git clone git@github.com:graphql-portal/graphql-portal-docker.git
cd graphql-portal-docker

docker-compose -f docker-compose.yml up
```

This will launch the Gateway, Dashboard, as well as Redis and MongoDB.

Where to go from here? We would suggest creating some APIs and playing with the data connectors.
[Read more about that here.](#configuration)
