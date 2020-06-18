# elk-compose
A docker-compose file to run containers of ELK stack, with authorization enabled.

There are three possible configs:
- `elk-compose-config-1.yml`: authorization enabled, considering preexistent networks
- `elk-compose-config-2.yml`: authorization enabled, default networking
- `elk-compose-config-3.yml`: authorization disabled, default networking

To use configurations with authorization enabled, you must setup an username and password in the file `.env`.

```
docker-compose -f elk-compose-config-1.yml -p elk up -d
```
