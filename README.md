# frog-db

Docker with:
- Telegraf
- InfluxDB
- Grafana


```
+--------------------------+     +----------+     +---------+
|                          |     |          |     |         |
| telegraf with MQTT input | --> | influxDB | --> | grafana |
|                          |     |          |     |         |
+--------------------------+     +----------+     +---------+
```

## prepare

Pull Docker images:

```
docker pull influxdb
docker pull grafana/grafana
docker pull telegraf
```

## run

Start the Docker with: 

```
docker-compose up
```

Grafana: http://localhost:3000 
user: admin
password: admin
