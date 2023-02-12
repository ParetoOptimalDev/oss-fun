---
title: "Reproducible Project List"
date: 2023-02-11T21:30:35-06:00
---

# Reproducible Projects

NOTE: Before proceeding complete the [getting started guide for developers](/developers-get-started).

See [Reproducible project criteria](#reproducibility-criteria) for more information.

In the off chance something is not building for you and ruining your fun, shoot me an email so I can investigate [here](mailto:pareto.optimal@mailfence.com).

## Diffuse

A music player that connects to your cloud/distributed storage

Language: Elm

time to hacking: 10-15m

estimated disk usage: N/A

github: https://github.com/icidasset/diffuse

## selfoss

description: multipurpose rss reader, live stream, mashup, aggregation web application

time to hacking: 1m

Language: Elm

estimated disk usage: 1.2GB

github: https://github.com/fossar/selfoss

## smos

description: A comprehensive self-management System

time to hacking: 3m30s

Language: Haskell

estimated disk usage: 6GB

github: https://github.com/NorfairKing/smos

# Reproducibility Criteria

The above projects must:

- Contain `flake.nix` and `.envrc`
- ~~Have a 90% or higher build rate over the past month~~ (coming soon)
Note this list is a subset from [this search courtesy of sourcegraph](https://sourcegraph.com/search?q=context:global+repo:has.path%28flake.nix%29+and+repo:has.path%28.envrc%29+select:repo+&patternType=lucky&sm=0&groupBy=repo).
