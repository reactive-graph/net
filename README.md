<div align="center">
  <a href="https://www,reactive-graph.io/"><img src="https://raw.githubusercontent.com/reactive-graph/design/main/public/logo/rendered/malachite/reactive-graph-400x400.png" alt="Reactive Graph"></a>
</div>

<h2 align="center">
    Interface Plugins
</h2>

<p align="center">
This repository contains plugins for the <a href="https://github.com/reactive-graph/reactive-graph">Reactive Graph</a> that allows to interoperate with other systems.
</p>

<p align="center">
  <a href="https://github.com/reactive-graph/reactive-graph">Reactive Graph</a> is a <b>reactive runtime</b> based on a <b>graph database</b>, empowering everyone to build reliable and efficient software.
</p>

## Planned Plugins

| Protocol        | Description                                                                           | Status                                        | Technology                                                            | 
|-----------------|---------------------------------------------------------------------------------------|-----------------------------------------------|-----------------------------------------------------------------------|
| HTTP + JSON-RPC | Reactive Graph acts as client (send requests and get responses)                       | Already implemented. Move from `plugins-core` | https://github.com/reactive-graph/plugins-core/tree/main/plugins/http |
| GraphQL         | Reactive Graph acts as client (send queries, send mutations, subscribe subscriptions) | Not implemented                               | https://docs.rs/gql_client/latest/gql_client/                         |
| MQTT            | Reactive Graph acts as client (subscribing queues, send messages)                     | Not implemented                               | https://github.com/bytebeamio/rumqtt                                  |
| AMQP            | Reactive Graph acts as client (subscribing queues, send messages)                     | Not implemented                               | https://github.com/amqp-rs/lapin                                      |
| Telegraf        | Reactive Graph produces metrics                                                       | Not implemented                               | https://github.com/maxmindlin/telegraf-rust                           |
