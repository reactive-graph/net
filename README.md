# Reactive Graph - Plugins Interfaces

## About

This repository contains plugins that connects the Reactive Graph with other systems.

## Planned Plugins

| Protocol | Description | Status | Technology | 
| --- | --- | --- | --- |
| HTTP + JSON-RPC | Reactive Graph acts as client (send requests and get responses) | Already implemented. Move from `plugins-core` | https://github.com/reactive-graph/plugins-core/tree/main/plugins/http |
| GraphQL | Reactive Graph acts as client (send queries, send mutations, subscribe subscriptions) | Not implemented | https://docs.rs/gql_client/latest/gql_client/ |
| MQTT | Reactive Graph acts as client (subscribing queues, send messages) | Not implemented| https://github.com/bytebeamio/rumqtt |
| AMQP | Reactive Graph acts as client (subscribing queues, send messages) | Not implemented| https://github.com/amqp-rs/lapin |
| Telegraf | Reactive Graph produces metrics | Not implemented| https://github.com/maxmindlin/telegraf-rust |
