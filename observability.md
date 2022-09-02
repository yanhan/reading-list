## Prometheus

- https://sysrant.com/posts/prometheus-multi-cluster/

### Scale Prometheus

- https://prometheus.io/docs/prometheus/latest/federation/
- https://logz.io/blog/devops/prometheus-architecture-at-scale
- https://sysdig.com/blog/challenges-scale-prometheus/

### Cortex OOM issues with possible solutions

- https://github.com/cortexproject/cortex/issues/665 (ingester instance limits)
- https://github.com/cortexproject/cortex/issues/858 (ingester.instance-limits.max-inflight-push-requests)
- https://github.com/cortexproject/cortex/issues/1895 (Slow ingester causing OOM on distributors; possibly combine -distributor.instance-limits.max-inflight-push-requests, -ingester.instance-limits.max-inflight-push-requests, -ingester.max-concurrent-streams)

### Cortex example memory leaks

- https://github.com/cortexproject/cortex/pull/2839

### Cortex Load Testing example

- https://github.com/cortexproject/cortex/issues/4284
