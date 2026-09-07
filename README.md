# idref-docker
Configuration docker 🐳 pour déployer IdRef-API et data-idref

[![Docker Pulls](https://img.shields.io/docker/pulls/abesesr/idref.svg)](https://hub.docker.com/r/abesesr/idref/)

En local, il faut préciser la variable d'environnement à la JVM : -DENVIR="www-test"

| URLs               | Dev                                                            | Test                                                            | Prod                                                            |
|--------------------|----------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|
| WS Derivation BNF  | http://diplotaxis1-dev.v212.abes.fr:9520/derivationdoublon     | http://diplotaxis1-test.v202.abes.fr:9520/derivationdoublon     | http://diplotaxis1-prod.v102.abes.fr:9520/derivationdoublon     |
| WS Derivation VIAF | http://diplotaxis1-dev.v212.abes.fr:9521/derivationviafdoublon | http://diplotaxis1-test.v202.abes.fr:9521/derivationviafdoublon | http://diplotaxis1-prod.v102.abes.fr:9521/derivationviafdoublon |
| Data IdRef         | [data-dev.idref.fr](https://data-dev.idref.fr)                 | [data-test.idref.fr](https://data-test.idref.fr/)               | [data.idref.fr](https://data.idref.fr/)                                                                |

Repository des sources :
- [IdRef-API](https://github.com/Abesesr/idref-api)
- [data-idref](https://github.com/Abesesr/data-idref)
