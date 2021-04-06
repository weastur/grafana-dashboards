# Grafana dashboards

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Set of useful Grafana dashboards

## List

1. [ClickHouse](dashboards/clickhouse/clickhouse.json)

## Development

### Requirements

1. Docker
1. docker-compose

### Flow

1. Up environment
    ```bash
    docker-compose up -d
    ```
1. Go to Grafana: http://127.0.0.1:3000 (admin/admin)
1. Connect Prometheus: http://127.0.0.1:9090
1. Import dashboards.
1. Make your changes
1. Export your dashboard and save it to appropriate folder

## License

MIT, see [LICENSE](./LICENSE).
