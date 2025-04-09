Configure OTEL colector with local Prometheus and Grafana.

You can point your app to this collector and debug sended data.

```
OTEL_ENDPOINT=localhost:4317
OTEL_INSECURE=true
OTEL_SERVICE_NAME=app-local
```

