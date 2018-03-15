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

## run

Start the Docker with: 

```
docker-compose up
```

Grafana: http://localhost:3000 
user: admin
password: admin
