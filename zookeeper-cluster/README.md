#Zookeeper Cluster with Web
* [General info](#general-info)
* [Setup](#setup)
* [Sources] (#sources)

## General info
This will initialize a zookeeper cluster with 3 nodes at ports 2181, 2182 and 2183, alongwith web ui running at port 8080.
The default username and password is web and admin.
It uses named volumes named zookeeper1, zookeeper2 and zookeeper3 for persistence.
These settings can be changed in the docker-compose.yml file.


## Setup
To run this project, after cloning the project:

```
cd zookeeper-cluster
docker-compose up -d
```

## Sources
This has been built on the following repositories:

https://hub.docker.com/r/bitnami/zookeeper
https://hub.docker.com/r/tobilg/zookeeper-webui

