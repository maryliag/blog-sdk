```
export OTEL_EXPORTER_OTLP_PROTOCOL="http/protobuf"
export OTEL_SERVICE_NAME="test-sdk"
unset NODE_OPTIONS

export OTEL_TRACES_EXPORTER="otlp"
export OTEL_METRICS_EXPORTER="otlp"

# Update
export OTEL_EXPORTER_OTLP_ENDPOINT="https://<grafana-instance>.grafana.net/otlp"
export OTEL_EXPORTER_OTLP_HEADERS="Authorization=Basic ..."
```
