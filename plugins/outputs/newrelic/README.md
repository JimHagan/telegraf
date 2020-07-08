#New Relic output plugin

This plugins writes to New Relic Insights using the [Metrics API][].

To use this plugin you must first obtain an [Insights API Key][].

### Configuration
```toml
[[outputs.newrelic]]
  ## New Relic Insert API key
  insights_key = "insert api key"

  ## Prefix to add to add to metric name for easy identification.
  # metric_prefix = ""

  ## Timeout for writes to the New Relic API.
  # timeout = "15s"
```

[Metrics API]: https://docs.newrelic.com/docs/data-ingest-apis/get-data-new-relic/metric-api/introduction-metric-api
[Insert API Key]: https://docs.newrelic.com/docs/apis/get-started/intro-apis/types-new-relic-api-keys#user-api-key
