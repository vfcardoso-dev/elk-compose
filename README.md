# elk-compose
A docker-compose file to run containers of ELK stack, with authorization enabled.

Attention: this script file supposes that your docker instance already have networks named 'innercircle', 'elastic' and 'kibana'. You can remove the network entries in the script if you don't need it.

```
docker-compose -f elk-compose.yml -p elk up -d
```
