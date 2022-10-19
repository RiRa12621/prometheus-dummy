# prometheus-dummy
Prometheus docker compose with dummy app to scrape, to have something to query

This deploys a Prometheus and an example app.

## Run

You need [docker-compose](https://docs.docker.com/compose/install/).

Clone the repository:

```
git clone https://github.com/RiRa12621/prometheus-dummy.git
```

Enter the directory:

```shell
cd prometheus-dummy
```

Start the containers:

```shell
docker-compose up
```

Prometheus will be available under http:localhost:8080.



