export OTEL_EXPORTER_OTLP_PROTOCOL="http/protobuf"
export OTEL_SERVICE_NAME="test-auto"
export NODE_OPTIONS="--require @opentelemetry/auto-instrumentations-node/register"

export OTEL_TRACES_EXPORTER="otlp"
export OTEL_METRICS_EXPORTER="otlp"
export OTEL_NODE_RESOURCE_DETECTORS="env,host,os,serviceinstance"

# Update
export OTEL_EXPORTER_OTLP_ENDPOINT="https://<grafana-instance>.grafana.net/otlp"
export OTEL_EXPORTER_OTLP_HEADERS="Authorization=Basic ..."