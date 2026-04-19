# Apache Ignite (apache-ignite)
Apache Ignite is a distributed database for mission-critical high-velocity applications requiring in-memory performance. It provides ACID transactions, SQL queries, key-value storage, compute grid, and backpressured streaming across distributed clusters. Governed by the Apache Software Foundation under the Apache 2.0 license.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-ignite/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Caching, Compute Grid, Distributed Database, In-Memory, Open Source, SQL

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Ignite REST API
The Ignite 3 REST API provides HTTP endpoints for cluster initialization, cluster management, node management, SQL query execution, configuration management, and deployment unit management.

**Human URL:** [https://ignite.apache.org/docs/ignite3/3.1.0/developers-guide/rest/rest-api](https://ignite.apache.org/docs/ignite3/3.1.0/developers-guide/rest/rest-api)

#### Tags:

 - Cluster Management, Configuration, REST, SQL

#### Properties

- [Documentation](https://ignite.apache.org/docs/ignite3/3.1.0/developers-guide/rest/rest-api)
- [OpenAPI](openapi/apache-ignite-rest-api.yaml)

### Apache Ignite Java Client API
The Ignite Java client API provides native Java access to Ignite clusters for table operations, SQL queries, transactions, and compute task execution.

**Human URL:** [https://ignite.apache.org/docs/ignite3/3.1.0/developers-guide/clients/java](https://ignite.apache.org/docs/ignite3/3.1.0/developers-guide/clients/java)

#### Tags:

 - Java, SDK

#### Properties

- [Documentation](https://ignite.apache.org/docs/ignite3/3.1.0/developers-guide/clients/java)
- [GettingStarted](https://ignite.apache.org/docs/ignite3/3.1.0/getting-started/quick-start)

### Apache Ignite .NET Client API
The Ignite .NET client API provides native C# and .NET access to Ignite clusters for table operations, SQL queries, and distributed computing.

**Human URL:** [https://ignite.apache.org/docs/ignite3/3.1.0/developers-guide/clients/dotnet](https://ignite.apache.org/docs/ignite3/3.1.0/developers-guide/clients/dotnet)

#### Tags:

 - .NET, C#, SDK

#### Properties

- [Documentation](https://ignite.apache.org/docs/ignite3/3.1.0/developers-guide/clients/dotnet)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/ignite-3)
- [Documentation](https://ignite.apache.org/docs/ignite3/3.1.0/)
- [GettingStarted](https://ignite.apache.org/docs/ignite3/3.1.0/getting-started/quick-start)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)
- [Versioning](https://ignite.apache.org/releases/)
- [SpectralRules](rules/apache-ignite-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-ignite-vocabulary.yaml)
- [NaftikoCapability](capabilities/cluster-management.yaml)

## Features

| Name | Description |
|------|-------------|
| In-Memory Speed | Memory-first storage with MVCC for consistent high-velocity performance. |
| ACID Transactions | Full ACID transactions across distributed cluster nodes. |
| SQL Support | ANSI SQL-compliant queries across distributed tables with JDBC/ODBC drivers. |
| Key-Value Storage | Native key-value API for direct cache access without SQL overhead. |
| Compute Grid | Distributed compute tasks co-located with data for low-latency processing. |
| Multi-Language Clients | Native clients for Java, .NET, C++, and Python. |
| Schema Evolution | Online schema changes without cluster downtime. |
| Backpressured Streaming | Event stream ingestion and enrichment with flow control. |

## Use Cases

| Name | Description |
|------|-------------|
| Event Stream Processing | Ingest, enrich, and process high-velocity event streams with in-memory speed. |
| Microservices State Management | Distributed state store for microservices with ACID guarantees. |
| Session Management | High-speed session caching for web applications. |
| AI/ML Feature Store | Low-latency feature serving for machine learning model inference. |
| Real-Time Analytics | SQL analytics over continuously updated distributed datasets. |

## Integrations

| Name | Description |
|------|-------------|
| Spring Boot | Native Spring Boot integration for Ignite cluster connectivity. |
| Apache Kafka | Stream data from Kafka topics into Ignite tables for real-time processing. |
| JDBC | Standard JDBC driver for connecting SQL tools to Ignite clusters. |
| ODBC | ODBC driver for BI tool integration with Ignite SQL engine. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Ignite REST API](openapi/apache-ignite-rest-api.yaml)

### JSON Schema

39 schema files extracted from the REST API OpenAPI specification.

### JSON Structure

39 JSON Structure files converted from JSON Schema files.

### JSON-LD

- [Apache Ignite REST API Context](json-ld/apache-ignite-rest-api-context.jsonld)

### Examples

39 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Ignite REST API](capabilities/shared/rest-api.yaml) — 4 operations for cluster, SQL, and configuration management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Ignite Cluster Management](capabilities/cluster-management.yaml) | Apache Ignite REST API | 5 | Database Administrator, Platform Engineer |

## Vocabulary

- [Apache Ignite Vocabulary](vocabulary/apache-ignite-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Ignite Spectral Rules](rules/apache-ignite-spectral-rules.yml) — 23 rules across 10 categories enforcing Apache Ignite REST API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
