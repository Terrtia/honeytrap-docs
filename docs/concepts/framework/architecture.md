---
title: Architectures
---

{% capture overview %}
This page gives a basic overview of the Honeytrap Architecture.
{% endcapture %}

The following picture gives an overview of the Honeytrap framework.

<img src="/images/architecture/overview.png">


## Main concepts

The honeytrap mainly consists of three objects:

|-
| Object | Explanation
|:-:|:-
| [![Honeytrap Agent](/images/architecture/agent.png)](/docs/concepts/framework/honeytrap-agent/) | Follow [this guide](/docs/setup/go/install-agent/) to setup the Honeytrap Agent.\\  Test on another row.
| [![Honeytrap Server](/images/architecture/server.png)](/docs/concepts/framework/honeytrap-server/) | Follow [this guide](/docs/setup/docker-compose/landing/) to setup the Honeytrap Server.
| [![Honeytrap Sensor](/images/architecture/sensor.png)](/docs/concepts/framework/honeytrap-sensor/) | Follow [this guide](/docs/setup/sensor/install-sensor/) to setuop the Honeytrap Sensor.
|=

## Architectures

There are several ways of implementing the Honeytrap framework. The most common architectures are as follows:

|-
| Architecture | Explanation
|:-:|:-
| [![Agent - Server](/images/architecture/agent_server.png)](/docs/concepts/framework/architecture/agent-server/) | Follow [this guide](/docs/setup/go/install-agent/) to setup the Honeytrap Agent.
| [![Sensor - Server](/images/architecture/sensor_server.png)](/docs/concepts/framework/architecture/sensor-server/) | Follow [this guide](/docs/setup/sensor/install-sensor/) to setup the Honeytrap Sensor.
| [![Server (standalone)](/images/architecture/server.png)](/docs/concepts/framework/architecture/server-standalone/) | Follow [this guide](/docs/setup/docker-compose/landing/) to setup the Honeytrap Server.
|=