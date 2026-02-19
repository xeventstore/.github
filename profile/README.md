# XEventStore

XEventStore is an event-native database designed for line of business applications.

Built and designed for event sourcing and CQRS workloads, XEventStore aims to make event data truly accessible — not just storable. Where existing event stores treat querying and indexing as afterthoughts, XEventStore puts data durability, accessibility, and queryability at the center of its design.

## Project Status

> ⚠️ XEventStore is in active development toward its beta phase. APIs and internals are subject to change.

We're working through a milestone-driven plan covering everything from low-level storage foundations through to a gRPC protocol, stream management, and observability. If you'd like to follow progress, watch the [XEventStore](https://github.com/xeventstore/xeventstore) repository.

## Repositories

| Repository | Description | License |
|---|---|---|
| [XEventStore](https://github.com/xeventstore/xeventstore) | The core database — storage engine, WAL, page layer, and gRPC server | [BSL 1.1](https://github.com/xeventstore/xeventstore/blob/main/LICENSE.md) |

Client libraries for working with the XEventStore API are planned as free and open-source software (FOSS) and will appear here as they become available.

## Licensing

The XEventStore database is licensed under the [Business Source License 1.1](https://github.com/xeventstore/xeventstore/blob/main/LICENSE.md). It may be used freely for development, testing, and non-commercial projects. Production use by a commercial entity requires a commercial license. Each version converts to the MIT license three years after publication.

Client libraries will be released under permissive open-source licenses.

For commercial licensing inquiries, contact [sales@xeventstore.com](mailto:sales@xeventstore.com).

## Get in Touch

The best way to reach us right now is through [GitHub Issues](https://github.com/xeventstore/xeventstore/issues) on the main repository. We welcome questions, feedback, and discussion about the project's direction.