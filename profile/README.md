### Quickstart

[docker compose](https://docs.docker.com/compose/)[^1] is the fastest way to get started. The docker compose file will set up an installation with these commands[^2]:

```bash
wget https://raw.githubusercontent.com/ledgersmb/ledgersmb-docker/1.12/docker-compose.yml
docker compose up -d
```
From there, follow the [Next Steps](https://github.com/ledgersmb/LedgerSMB#next-steps).


### For developers

The [dockerized LedgerSMB development
infrastructure](https://github.com/ledgersmb/ledgersmb-dev-docker#ledgersmb-docker-development--testing-infrastructure)
helps developers to get started quickly.

[^1]: See [the docker compose installation instructions](https://docs.docker.com/compose/install/) in case you don't already have it installed.
[^2]: If you need to change container parameters, you can find instructions in the docker compose file. 
