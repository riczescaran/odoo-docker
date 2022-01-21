# Odoo + Nginx Reverse Proxy

## Requirements
- docker
- docker-compose

## Installation
1. Adjust your `host` file and set
```sh
127.0.0.1 odoo.docker
127.0.0.1 pgadmin.odoo.docker
```

2. Rename `.env.example` into `.env` and adjust the variables to your needs. 

3. Start the docker container

```sh
docker-compose up -d
```

4. Open your browser and navigate to http://odoo.docker for the Odoo installation. \
For pgAdmin dashboard navigate to http://pgadmin.odoo.docker
