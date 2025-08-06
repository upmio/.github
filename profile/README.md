# Run Databases & Middleware in Kubernetes!

Welcome to **UPMIO**, a comprehensive open source platform designed to
seamlessly manage databases and middleware within Kubernetes environments,
covering the entire operational lifecycle from initial deployment to ongoing
maintenance.

UPM (Unified Platform Management) provides cloud-native automated operations
and management capabilities for MySQL, Redis, Kafka, Zookeeper, Elasticsearch,
and other data services.

The main components are the [unit-operator](https://github.com/upmio/unit-operator)
and [compose-operator](https://github.com/upmio/compose-operator).

## Core Projects

### [unit-operator](https://github.com/upmio/unit-operator)
Universal workload Operator that provides Unit and UnitSet custom resources,
supporting unified orchestration and management of various databases and middleware.

### [compose-operator](https://github.com/upmio/compose-operator)
Advanced operations Operator that provides automated management for complex
operational scenarios such as MySQL master-slave replication, Redis clusters,
and ProxySQL synchronization.

## Architecture

UPM adopts a "Hub-Agent" distributed architecture with separation of control
plane and data plane:

- **UPM Platform**: Control plane providing declarative APIs and workflow orchestration
- **UPM Engine**: Data plane implementing state reconciliation based on Kubernetes Operators

## Contributing

You can contribute to UPMIO in many ways:

- Raising any issues you find using UPMIO
- Fixing issues by opening Pull Requests
- Improving documentation
- Talking about UPMIO

## License

UPMIO is licensed under the [Apache License, Version 2.0](https://github.com/upmio/.github/blob/main/LICENSE).