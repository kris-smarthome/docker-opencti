# docker-opencti
docker compose files, local opencti install 

Services:
- OpenCTI: Open Threat Intelligence platform

Connectors:
- Shodan

## usage
Clone this repository to your local machine, edit the config file to match your environment, and run docker compose.

```bash
git clone https://github.com/kris-smarthome/docker-opencti.git opencti/
cd opencti
nano .env
docker compose up -d
```

> [!NOTE]
> This stack assumes the use of Traefik, remove labels and networks if Traefik is not used. 
