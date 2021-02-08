---
uid: MQTTConfiguration
---

# Configuration

PI Adapter for MQTT provides configuration of data source, client settings, discovery, and data selection for both components the generic and the Sparkplug B component.

The examples in the configuration topics use `curl`, a commonly available tool on both Windows and Linux. You can configure the adapter with any programming language or tool that supports making REST calls or with the EdgeCmd utility. For more information, see the [EdgeCmd utility documentation (https://osisoft.github.io/Edgecmd-Docs/V1.1/edgecmd-utility.html)](https://osisoft.github.io/Edgecmd-Docs/V1.1/edgecmd-utility.html). To validate successful configurations, you can perform data retrieval (`GET` commands) with a browser, if available, on your device.

For more information on PI Adapter configuration tools, see [Configuration tools](xref:ConfigurationTools).

## Quick start

Complete the following steps to establish a data flow from a MQTT data source device to a data endpoint.

1. Configure one or several MQTT system components.<br>See [System components configuration](xref:SystemComponentsConfiguration#add-a-system-component).

2. Configure an MQTT data source for each MQTT device.<br>See [PI Adapter for MQTT data source configuration](xref:PIAdapterForMQTTDataSourceConfiguration#configure-mqtt-data-source) and [PI Adapter for MQTT Sparkplug B data source configuration](xref:PIAdapterForMQTTSparkplugBDataSourceConfiguration#configure-mqtt-sparkplug-b-data-source).

3. Optional: Change the automatically generated and configured MQTT client settings. See [PI Adapter for MQTT client settings configuration](xref:PIAdapterForMQTTClientSettingsConfiguration).

4. Optional: Perform a data discovery. See [Discovery configuration](xref:DiscoveryConfiguration).

5. Configure an MQTT data selection for each MQTT data source.<br>See [PI Adapter for MQTT data selection configuration](xref:PIAdapterForMQTTDataSelectionConfiguration#configure-mqtt-data-selection) and [PI Adapter for MQTT Sparkplug B data selection configuration](xref:PIAdapterForMQTTSparkplugBDataSelectionConfiguration#configure-mqtt-sparkplug-b-data-selection).

6. Configure one or several egress endpoints.<br>See [Egress endpoints configuration](xref:EgressEndpointsConfiguration).