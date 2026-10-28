# debezium-graal-mapper (deprecated)

> **This repository is no longer maintained and is kept for reference only.**
> The graal Data Platform now provides change data capture (CDC) into Apache Iceberg tables
> natively, and no longer uses Apache Pulsar. See
> [Capabilities](https://graal.systems/en/docs/scope) and
> [Connectors](https://graal.systems/en/platform/connectors).

This was a `StreamNameMapper` for [Debezium Server](https://debezium.io/documentation/reference/stable/operations/debezium-server.html)
that prefixed change-event topics with a Pulsar tenant and namespace
(`mapper.tenant` / `mapper.namespace` → `tenant/namespace/topic`), for the Pulsar-based CDC of
earlier graal versions.
