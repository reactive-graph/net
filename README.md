<div align="center">
  <a href="https://www,reactive-graph.io/"><img src="https://raw.githubusercontent.com/reactive-graph/design/main/public/logo/rendered/malachite/reactive-graph-400x400.png" alt="Reactive Graph"></a>
</div>

<h2 align="center">
    <a href="https://net.reactive-graph.io/">net.reactive-graph.io</a>
</h2>

<p align="center">
This repository contains plugins for the <a href="https://github.com/reactive-graph/reactive-graph">Reactive Graph</a> that allows to interoperate with other systems.
</p>

<p align="center">
  <a href="https://github.com/reactive-graph/reactive-graph">Reactive Graph</a> is a <b>reactive runtime</b> based on a <b>graph database</b>, empowering everyone to build reliable and efficient software.
</p>

<hr>

<div align="center" style="text-align: center">

[<img src="https://img.shields.io/badge/book-master-yellow">](https://net.reactive-graph.io/book/)
[<img src="https://img.shields.io/badge/api-master-yellow">](https://net.reactive-graph.io/docs/)

[<img src="https://img.shields.io/badge/Language-Rust-brightgreen">](https://www.rust-lang.org/)
[<img src="https://img.shields.io/badge/Platforms-Linux%20%26%20Windows-brightgreen">]()
[<img src="https://img.shields.io/github/license/reactive-graph/net">](https://github.com/reactive-graph/net/blob/main/LICENSE)

[![Build](https://github.com/reactive-graph/net/actions/workflows/rust.yml/badge.svg)](https://github.com/reactive-graph/net/actions/workflows/rust.yml)
[<img src="https://img.shields.io/discord/698219248954376256?logo=discord">](https://discord.com/invite/acUW8k7)

</div>

<hr>

<h2 align="center" style="text-align: center;">List of Plugins</h2>

| Protocol        | Description                               | Technology                                                            | 
|-----------------|-------------------------------------------|-----------------------------------------------------------------------|
| HTTP + JSON-RPC | Send HTTP requests and get HTTP responses | https://github.com/reactive-graph/plugins-core/tree/main/plugins/http |
| Git             | Clone and modify git repositories         | https://github.com/reactive-graph/plugins-core/tree/main/plugins/git  |

<h2 align="center" style="text-align: center;">Planned Plugins</h2>

| Protocol        | Description                                                                           | Status                                        | Technology                                                            | 
|-----------------|---------------------------------------------------------------------------------------|-----------------------------------------------|-----------------------------------------------------------------------|
| GraphQL         | Reactive Graph acts as client (send queries, send mutations, subscribe subscriptions) | Not implemented                               | https://docs.rs/gql_client/latest/gql_client/                         |
| MQTT            | Reactive Graph acts as client (subscribing queues, send messages)                     | Not implemented                               | https://github.com/bytebeamio/rumqtt                                  |
| AMQP            | Reactive Graph acts as client (subscribing queues, send messages)                     | Not implemented                               | https://github.com/amqp-rs/lapin                                      |
| Telegraf        | Reactive Graph produces metrics                                                       | Not implemented                               | https://github.com/maxmindlin/telegraf-rust                           |
