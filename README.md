# postgres-operator-image

This repository exists to build and host [Postgres
Operator](https://github.com/zalando/postgres-operator/) images for managing
FINN databases. Currently it uses a
[fork](https://github.com/finn-no/postgres-operator/) to maintain patches that
have not been merged upstream. 

Outstanding patches:

* [Add support for manually setting load balancer IPs](https://github.com/zalando/postgres-operator/pull/1528)
