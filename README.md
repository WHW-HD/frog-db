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
