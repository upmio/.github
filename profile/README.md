[![Latest Release](https://img.shields.io/github/v/release/upmio/upm.svg)](https://github.com/upmio/upm/releases)
[![GitHub License](https://img.shields.io/github/license/upmio/upm)](https://github.com/upmio/upm/blob/main/LICENSE)
[![Documentation](https://img.shields.io/badge/docs-upmio.github.io-blue)](https://upmio.github.io)
[![Go Report Card](https://goreportcard.com/badge/github.com/upmio/upm)](https://goreportcard.com/report/github.com/upmio/upm)
[![GitHub Stars](https://img.shields.io/github/stars/upmio/upm?style=social)](https://github.com/upmio/upm)

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

## Adopters

A list of publicly known users of UPMIO is in [ADOPTERS.md](https://github.com/upmio/upm/blob/main/ADOPTERS.md).
Help us grow our community and UPMIO by adding yourself and your organization
to this list!

## Getting in touch

- [GitHub Discussions](https://github.com/upmio/upm/discussions)
- [Documentation](https://upmio.github.io)
- [Contributing Guide](https://github.com/upmio/upm/blob/main/CONTRIBUTING.md)

## Contributing

You can contribute to UPMIO in many ways:

- Raising any issues you find using UPMIO
- Fixing issues by opening Pull Requests
- Improving documentation
- Talking about UPMIO

## License

UPMIO is licensed under the [Apache License, Version 2.0](https://github.com/upmio/upm/blob/main/LICENSE).