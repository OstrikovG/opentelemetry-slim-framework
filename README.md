### Run server

```bash
$ env OTEL_PHP_AUTOLOAD_ENABLED=true \
$ OTEL_TRACES_EXPORTER=console \
$ OTEL_METRICS_EXPORTER=none \
$ OTEL_LOGS_EXPORTER=none \
$ php -S localhost:8080
```