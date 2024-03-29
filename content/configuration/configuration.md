---
uid: MQTTConfiguration
---

# Configuration

PI Adapter for MQTT provides configuration of data source, discovery, and data selection for both the generic and the Sparkplug B component.

The examples in the configuration topics use `curl`, a commonly available tool on both Windows and Linux. You can configure the adapter with any programming language or tool that supports making REST calls or with the EdgeCmd utility. For more information, see the [EdgeCmd utility documentation](https://docs.osisoft.com/bundle/edgecmd/page/index.html). To validate successful configurations, you can perform data retrieval (`GET` commands) with a browser, if available, on your device.

For more information on PI Adapter configuration tools, see [Configuration tools](xref:ConfigurationTools).

## Quick start

This Quick Start guides you through setup of each configuration file available for PI Adapter for MQTT. As you complete each step, perform each required configuration to establish a data flow from a data source to one or more endpoints. Some configurations are optional.

**Important:** If you want to complete the optional configurations, complete those tasks before the required tasks.

1. Configure one or more MQTT system components.<br>See [System components](xref:SystemComponentsConfiguration#configure-system-components).

2. Configure an MQTT data source for each MQTT device.<br>See [Data source (generic)](xref:PIAdapterForMQTTDataSourceConfiguration#configure-mqtt-data-source) and [Data source (Sparkplug B)](xref:PIAdapterForMQTTSparkplugBDataSourceConfiguration#configure-mqtt-sparkplug-b-data-source).

3. **Optional**: Configure data discovery. See [Discovery](xref:DiscoveryConfiguration#configure-discovery).

4. Configure an MQTT data selection for each MQTT data source.<br>See [Data selection (generic)](xref:PIAdapterForMQTTDataSelectionConfiguration#configure-mqtt-data-selection) and [Data selection (Sparkplug B)](xref:PIAdapterForMQTTSparkplugBDataSelectionConfiguration#configure-mqtt-sparkplug-b-data-selection).

5. **Optional**: Configure data filters, diagnostics and metadata, buffering, logging, and if there is a proxy between the adapter and your egress endpoints, define it.<br>See the following topics:

    - [Data filters](xref:DataFiltersConfiguration#configure-data-filters)
    - [Diagnostics and metadata](xref:GeneralConfiguration#configure-general)
    - [Buffering](xref:BufferingConfiguration#configure-buffering)
    - [Logging](xref:LoggingConfiguration#configure-logging)
    - [Configure a network proxy](xref:ConfigureANetworkProxy)

6. Configure one or more egress and health endpoints. <br>See [Egress endpoints](xref:EgressEndpointsConfiguration#configure-egress-endpoints) and [Health endpoints](xref:HealthEndpointConfiguration#configure-health-endpoint).
