# cloudquery-docker-compose

## Requirements

 - https://www.docker.com/

## Install

### Azure

Seleccionamos la suscripción de Azure a operar.
```
$ source azureTemplate.credential

$ export AZURE_SUBSCRIPTION_ID=< SUBSCRIPTION_ID >
```

### GCP

Seleccionamos el proyecto de GCP a operar.
```
$ source gcpTemplate.credential
```

### AWS

Seleccionamos la cuenta de AWS a operar.
```
$ source awsTemplate.credential
```

## Run
```
$ docker compose run --rm cloudquery fetch --config /config/cloudquery.yml
```

### Clean
```
$ source clean.credential
```

## Documentation
* https://docs.cloudquery.io/docs/intro