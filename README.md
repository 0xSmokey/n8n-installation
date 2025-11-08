### Production n8n setup using docker compose 

using this setup you can easily setup production self host n8n 

- install docker 
- install docker compose 

- clone this repo 

update .env file

ENV file ".env"

```DOMAIN_NAME=domain.com
SUBDOMAIN=subdomain
SSL_EMAIL=name@domain.com

POSTGRES_USER=postgress_user
POSTGRES_PASSWORD=paswd
POSTGRES_DB=n8n_database

GENERIC_TIMEZONE=timeZone
```

### run n8n 

- docker-compose -d up 