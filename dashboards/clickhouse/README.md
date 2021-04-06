# ClickHouse

ClickHouse overview dashboard for internal exporter

## Requirements (tested, but may work on older versions too)

1. Grafana - 7 and up
1. ClickHouse - 21.3.4.25-lts and up
1. Prometheus
1. ClickHouse internal exporter ([how to](https://clickhouse.tech/docs/en/operations/server-configuration-parameters/settings/#server_configuration_parameters-prometheus))

## Features

1. Info for: Queries (plus Select/Insert details), IO, Replicas, Merges, Zookeeper, Cache, Parts, Distributed tables, Background task pools
1. Show both trends and peaks (configurable)
1. `max_over_time` + PromQL subqueries to get all peaks
1. `$__rate_interval` to correct rate calc between points
1. `Max data points` set to 200 for all graph panel
1. Table with overall info for selected instances
1. Annotation for restart event
