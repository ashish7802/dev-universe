# DevOps — Monitoring, Logging & Observability

> Comprehensive collection of metrics, logging, tracing, alerting, dashboards, APM, uptime monitoring, and full-stack observability tools.

---

## Metrics & Time Series Databases

| Repository | Description | Stars |
|------------|-------------|-------|
| [prometheus/prometheus](https://github.com/prometheus/prometheus) | The monitoring system and time series database — industry standard | ![Stars](https://img.shields.io/github/stars/prometheus/prometheus?style=flat-square) |
| [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) | Fast, cost-effective monitoring solution — Prometheus-compatible | ![Stars](https://img.shields.io/github/stars/VictoriaMetrics/VictoriaMetrics?style=flat-square) |
| [influxdata/influxdb](https://github.com/influxdata/influxdb) | Purpose-built time series database — IoT, analytics, devops | ![Stars](https://img.shields.io/github/stars/influxdata/influxdb?style=flat-square) |
| [questdb/questdb](https://github.com/questdb/questdb) | High-performance time series database — 4.3M rows/sec | ![Stars](https://img.shields.io/github/stars/questdb/questdb?style=flat-square) |
| [timescale/timescaledb](https://github.com/timescale/timescaledb) | PostgreSQL extension for time series — SQL on time series | ![Stars](https://img.shields.io/github/stars/timescale/timescaledb?style=flat-square) |
| [m3db/m3](https://github.com/m3db/m3) | Uber's distributed TSDB — long-term Prometheus storage | ![Stars](https://img.shields.io/github/stars/m3db/m3?style=flat-square) |
| [cortexproject/cortex](https://github.com/cortexproject/cortex) | Horizontally scalable, multi-tenant Prometheus | ![Stars](https://img.shields.io/github/stars/cortexproject/cortex?style=flat-square) |
| [thanos-io/thanos](https://github.com/thanos-io/thanos) | Highly available Prometheus with long-term storage | ![Stars](https://img.shields.io/github/stars/thanos-io/thanos?style=flat-square) |

---

## Dashboards & Visualization

| Repository | Description | Stars |
|------------|-------------|-------|
| [grafana/grafana](https://github.com/grafana/grafana) | The open and composable observability platform — most used | ![Stars](https://img.shields.io/github/stars/grafana/grafana?style=flat-square) |
| [netdata/netdata](https://github.com/netdata/netdata) | Real-time performance monitoring — 2000+ metrics per node | ![Stars](https://img.shields.io/github/stars/netdata/netdata?style=flat-square) |
| [grafana/k6](https://github.com/grafana/k6) | Load testing tool with Grafana integration — performance metrics | ![Stars](https://img.shields.io/github/stars/grafana/k6?style=flat-square) |
| [metabase/metabase](https://github.com/metabase/metabase) | Business intelligence tool — charts and dashboards from DB | ![Stars](https://img.shields.io/github/stars/metabase/metabase?style=flat-square) |
| [apache/superset](https://github.com/apache/superset) | Data visualization and exploration platform | ![Stars](https://img.shields.io/github/stars/apache/superset?style=flat-square) |
| [chronograf](https://github.com/influxdata/chronograf) | InfluxDB's UI and visualization tool | ![Stars](https://img.shields.io/github/stars/influxdata/chronograf?style=flat-square) |

---

## Logging

| Repository | Description | Stars |
|------------|-------------|-------|
| [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | Distributed search and analytics — core of ELK stack | ![Stars](https://img.shields.io/github/stars/elastic/elasticsearch?style=flat-square) |
| [elastic/kibana](https://github.com/elastic/kibana) | Visualize Elasticsearch data — logs, metrics, APM | ![Stars](https://img.shields.io/github/stars/elastic/kibana?style=flat-square) |
| [elastic/logstash](https://github.com/elastic/logstash) | Log processing pipeline — ingest, transform, ship | ![Stars](https://img.shields.io/github/stars/elastic/logstash?style=flat-square) |
| [grafana/loki](https://github.com/grafana/loki) | Like Prometheus but for logs — label-based indexing | ![Stars](https://img.shields.io/github/stars/grafana/loki?style=flat-square) |
| [fluent/fluentd](https://github.com/fluent/fluentd) | Unified logging layer — connects everything to Elasticsearch | ![Stars](https://img.shields.io/github/stars/fluent/fluentd?style=flat-square) |
| [fluent/fluent-bit](https://github.com/fluent/fluent-bit) | Lightweight log processor and forwarder — perfect for K8s | ![Stars](https://img.shields.io/github/stars/fluent/fluent-bit?style=flat-square) |
| [vectordotdev/vector](https://github.com/vectordotdev/vector) | High-performance observability data pipeline — 10x faster | ![Stars](https://img.shields.io/github/stars/vectordotdev/vector?style=flat-square) |
| [getsentry/sentry](https://github.com/getsentry/sentry) | Error tracking and performance monitoring — self-hostable | ![Stars](https://img.shields.io/github/stars/getsentry/sentry?style=flat-square) |
| [papertrail/remote_syslog2](https://github.com/papertrail/remote_syslog2) | Remote syslog daemon — ship logs to cloud | ![Stars](https://img.shields.io/github/stars/papertrail/remote_syslog2?style=flat-square) |
| [nicolo-ribaudo/loguru](https://github.com/Delgan/loguru) | Python logging made simple — drop-in replacement for logging | ![Stars](https://img.shields.io/github/stars/Delgan/loguru?style=flat-square) |
| [sirupsen/logrus](https://github.com/sirupsen/logrus) | Structured, pluggable logging for Go | ![Stars](https://img.shields.io/github/stars/sirupsen/logrus?style=flat-square) |
| [rs/zerolog](https://github.com/rs/zerolog) | Zero allocation JSON logger for Go | ![Stars](https://img.shields.io/github/stars/rs/zerolog?style=flat-square) |

---

## Distributed Tracing

| Repository | Description | Stars |
|------------|-------------|-------|
| [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) | Open source distributed tracing by Uber — CNCF graduated | ![Stars](https://img.shields.io/github/stars/jaegertracing/jaeger?style=flat-square) |
| [openzipkin/zipkin](https://github.com/openzipkin/zipkin) | Distributed tracing system — Twitter origin | ![Stars](https://img.shields.io/github/stars/openzipkin/zipkin?style=flat-square) |
| [open-telemetry/opentelemetry-collector](https://github.com/open-telemetry/opentelemetry-collector) | Vendor-agnostic telemetry collection — traces, metrics, logs | ![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector?style=flat-square) |
| [open-telemetry/opentelemetry-python](https://github.com/open-telemetry/opentelemetry-python) | OpenTelemetry Python SDK — instrument any app | ![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-python?style=flat-square) |
| [open-telemetry/opentelemetry-js](https://github.com/open-telemetry/opentelemetry-js) | OpenTelemetry JavaScript SDK | ![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-js?style=flat-square) |
| [grafana/tempo](https://github.com/grafana/tempo) | Distributed tracing backend — integrates with Grafana | ![Stars](https://img.shields.io/github/stars/grafana/tempo?style=flat-square) |
| [nicolo-ribaudo/skywalking](https://github.com/apache/skywalking) | Application Performance Monitor for distributed systems | ![Stars](https://img.shields.io/github/stars/apache/skywalking?style=flat-square) |

---

## Alerting

| Repository | Description | Stars |
|------------|-------------|-------|
| [prometheus/alertmanager](https://github.com/prometheus/alertmanager) | Handle Prometheus alerts — routing, grouping, silencing | ![Stars](https://img.shields.io/github/stars/prometheus/alertmanager?style=flat-square) |
| [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) | Self-hosted uptime monitoring — beautiful status page | ![Stars](https://img.shields.io/github/stars/louislam/uptime-kuma?style=flat-square) |
| [keephq/keep](https://github.com/keephq/keep) | Open source alert management and automation — AIOps | ![Stars](https://img.shields.io/github/stars/keephq/keep?style=flat-square) |
| [grafana/oncall](https://github.com/grafana/oncall) | Developer-friendly incident response — on-call scheduling | ![Stars](https://img.shields.io/github/stars/grafana/oncall?style=flat-square) |
| [nicolo-ribaudo/cabot](https://github.com/arachnys/cabot) | Self-hosted Nagios alternative — health checks and alerts | ![Stars](https://img.shields.io/github/stars/arachnys/cabot?style=flat-square) |
| [nicolo-ribaudo/statping](https://github.com/statping-ng/statping-ng) | Status page and monitoring — self-hosted | ![Stars](https://img.shields.io/github/stars/statping-ng/statping-ng?style=flat-square) |

---

## APM & Error Tracking

| Repository | Description | Stars |
|------------|-------------|-------|
| [getsentry/sentry](https://github.com/getsentry/sentry) | Error monitoring + performance APM — most used open source APM | ![Stars](https://img.shields.io/github/stars/getsentry/sentry?style=flat-square) |
| [highlight/highlight](https://github.com/highlight/highlight) | Full-stack monitoring — session replay, errors, logs, traces | ![Stars](https://img.shields.io/github/stars/highlight/highlight?style=flat-square) |
| [PostHog/posthog](https://github.com/PostHog/posthog) | Product analytics + session recording — open source Mixpanel | ![Stars](https://img.shields.io/github/stars/PostHog/posthog?style=flat-square) |
| [nicolo-ribaudo/glitchtip](https://github.com/glitchtip/glitchtip-backend) | Open source Sentry alternative — error tracking | ![Stars](https://img.shields.io/github/stars/glitchtip/glitchtip-backend?style=flat-square) |
| [nicolo-ribaudo/openreplay](https://github.com/openreplay/openreplay) | Open source session replay — see user issues in real time | ![Stars](https://img.shields.io/github/stars/openreplay/openreplay?style=flat-square) |

---

## Infrastructure Monitoring

| Repository | Description | Stars |
|------------|-------------|-------|
| [prometheus/node_exporter](https://github.com/prometheus/node_exporter) | Prometheus exporter for hardware and OS metrics | ![Stars](https://img.shields.io/github/stars/prometheus/node_exporter?style=flat-square) |
| [google/cadvisor](https://github.com/google/cadvisor) | Container Advisor — resource usage of running containers | ![Stars](https://img.shields.io/github/stars/google/cadvisor?style=flat-square) |
| [nicolo-ribaudo/collectd](https://github.com/collectd/collectd) | System statistics collection daemon | ![Stars](https://img.shields.io/github/stars/collectd/collectd?style=flat-square) |
| [nicolo-ribaudo/telegraf](https://github.com/influxdata/telegraf) | Plugin-driven server agent for metrics collection | ![Stars](https://img.shields.io/github/stars/influxdata/telegraf?style=flat-square) |
| [nicolo-ribaudo/statsd](https://github.com/statsd/statsd) | Network daemon for aggregating stats — Node.js | ![Stars](https://img.shields.io/github/stars/statsd/statsd?style=flat-square) |
| [nicolo-ribaudo/glances](https://github.com/nicolargo/glances) | Cross-platform system monitoring tool — web UI included | ![Stars](https://img.shields.io/github/stars/nicolargo/glances?style=flat-square) |
| [aristocratos/btop](https://github.com/aristocratos/btop) | Resource monitor — beautiful terminal dashboard | ![Stars](https://img.shields.io/github/stars/aristocratos/btop?style=flat-square) |

---

## Synthetic & Uptime Monitoring

| Repository | Description | Stars |
|------------|-------------|-------|
| [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) | Self-hosted monitoring — HTTP, TCP, DNS, ping checks | ![Stars](https://img.shields.io/github/stars/louislam/uptime-kuma?style=flat-square) |
| [nicolo-ribaudo/gatus](https://github.com/TwiN/gatus) | Automated service health dashboard | ![Stars](https://img.shields.io/github/stars/TwiN/gatus?style=flat-square) |
| [nicolo-ribaudo/upptime](https://github.com/upptime/upptime) | GitHub Actions powered uptime monitor and status page | ![Stars](https://img.shields.io/github/stars/upptime/upptime?style=flat-square) |
| [nicolo-ribaudo/checkly](https://github.com/checkly/checkly-cli) | Monitoring as code — API and browser checks | ![Stars](https://img.shields.io/github/stars/checkly/checkly-cli?style=flat-square) |

---

## Load Testing & Performance

| Repository | Description | Stars |
|------------|-------------|-------|
| [grafana/k6](https://github.com/grafana/k6) | Developer-centric load testing tool — JS scripting | ![Stars](https://img.shields.io/github/stars/grafana/k6?style=flat-square) |
| [locustio/locust](https://github.com/locustio/locust) | Scalable load testing in Python — real browser behavior | ![Stars](https://img.shields.io/github/stars/locustio/locust?style=flat-square) |
| [nicolo-ribaudo/artillery](https://github.com/artilleryio/artillery) | Cloud-scale load testing — HTTP, WebSocket, gRPC | ![Stars](https://img.shields.io/github/stars/artilleryio/artillery?style=flat-square) |
| [nicolo-ribaudo/vegeta](https://github.com/tsenart/vegeta) | HTTP load testing tool and library — Go | ![Stars](https://img.shields.io/github/stars/tsenart/vegeta?style=flat-square) |
| [nicolo-ribaudo/wrk](https://github.com/wg/wrk) | Modern HTTP benchmarking tool | ![Stars](https://img.shields.io/github/stars/wg/wrk?style=flat-square) |
| [nicolo-ribaudo/hyperfine](https://github.com/sharkdp/hyperfine) | Command-line benchmarking tool — statistical analysis | ![Stars](https://img.shields.io/github/stars/sharkdp/hyperfine?style=flat-square) |

---

## OpenTelemetry Ecosystem

| Repository | Description | Stars |
|------------|-------------|-------|
| [open-telemetry/opentelemetry-specification](https://github.com/open-telemetry/opentelemetry-specification) | Specification for OpenTelemetry — standards and docs | ![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-specification?style=flat-square) |
| [open-telemetry/opentelemetry-collector-contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib) | Community contrib components for OTel collector | ![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector-contrib?style=flat-square) |
| [open-telemetry/opentelemetry-go](https://github.com/open-telemetry/opentelemetry-go) | OpenTelemetry Go SDK | ![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-go?style=flat-square) |
| [nicolo-ribaudo/odigos](https://github.com/keyval-dev/odigos) | Instant distributed tracing — no code changes needed | ![Stars](https://img.shields.io/github/stars/keyval-dev/odigos?style=flat-square) |

---

[← Back to Index](../README.md)
