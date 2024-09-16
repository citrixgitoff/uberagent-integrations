## uberAgent Integrations and Dashboards

uberAgent is a User Experience Monitoring (UXM) and Endpoint Security Analytics (ESA) tool that provides in-depth visibility into user experience, system performance, and security across physical and virtual endpoints.

uberAgent can send collected metrics directly to **platforms** like:
* Splunk
* Elastic
* Azure Monitor (Log Analytics)

uberAgent can also send collected metrics to other platforms indirectly, via the supported Kafka interface:
* Dynatrace
* Datadog

Pre-built dashboards are available for the above platforms, backed by different Visualization tools:

| Platform / Backend | Visualization |
| ---------------- | ------------- |
| [Splunk](https://docs.citrix.com/en-us/uberagent/current-release/installation/backend/configuring-splunk-http-event-collector)   | uberAgent UXM and ESA [Splunk apps](https://docs.citrix.com/en-us/uberagent/current-release/installation/installing-uberagent/installing-the-splunk-apps) |
| [Elasticsearch](https://docs.citrix.com/en-us/uberagent/current-release/installation/backend/installing-elasticsearch) | [Kibana dashboards](elastic/kibana) |
| [Azure Monitor (Log Analytics)](https://docs.citrix.com/en-us/uberagent/current-release/installation/backend/configuring-microsoft-azure-oms-log-analytics) | [Azure Workbooks](azure-monitor/azure-workbooks) |
| [Azure Monitor (Log Analytics)](https://docs.citrix.com/en-us/uberagent/current-release/installation/backend/configuring-microsoft-azure-oms-log-analytics) | [Grafana](azure-monitor/grafana) |
| [Azure Monitor (Log Analytics)](https://docs.citrix.com/en-us/uberagent/current-release/installation/backend/configuring-microsoft-azure-oms-log-analytics) | [PowerBI](azure-monitor/powerbi) |
| Datadog | [Datadog Dashboards](datadog)
| Dynatrace | [Dynatrace Dashboards](dynatrace)