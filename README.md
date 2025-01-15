# veld_code__simple_docker_test

This repo contains [code velds](https://zenodo.org/records/13322913) provides a simple docker test
to print information from within the container. Maybe of help as a template when it comes to 
problems with other veld / docker setups.

## requirements

- git
- docker compose (note: older docker compose versions require running `docker-compose` instead of 
  `docker compose`)

## how to use

A code veld may be integrated into a chain veld, or used directly by adapting the configuration 
within its yaml file and using the template folders provided in this repo. Open the respective veld 
yaml file for more information.

## contained code velds

**[./veld.yaml](./veld.yaml)** 

Prints python interpreter information from within the container.

```
docker compose -f veld.yaml up
```

