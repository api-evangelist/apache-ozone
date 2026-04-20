# Apache Ozone (apache-ozone)
Apache Ozone is a scalable, redundant, and distributed object store optimized for big data workloads. It provides an S3-compatible interface and a Hadoop-compatible file system interface for seamless integration with existing big data tools.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-ozone/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-ozone/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Distributed Storage, Hadoop, Object Storage, S3-Compatible, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Ozone
Ozone provides an S3-compatible REST API for object storage operations, a Hadoop-compatible File System API (o3fs, ofs), a Java client API for bucket and key management, and a Recon REST API for cluster monitoring.

**Human URL:** [https://ozone.apache.org/docs/current/](https://ozone.apache.org/docs/current/)

#### Tags:

 - Hadoop, Object Storage, REST, S3, Apache, Open Source

#### Properties

- [Documentation](https://ozone.apache.org/docs/current/)
- [OpenAPI](openapi/apache-ozone-s3-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/ozone)
- [Documentation](https://ozone.apache.org/)
- [SpectralRules](rules/apache-ozone-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-ozone-vocabulary.yaml)
- [NaftikoCapability](capabilities/ozone-workflow.yaml)
- [JSON-LD](json-ld/apache-ozone-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| S3-Compatible API | Fully compatible with Amazon S3 API for object storage operations |
| HDFS-Compatible | Hadoop-compatible file system interface (o3fs, ofs) for existing Hadoop workloads |
| Multi-Tenant | Volume/bucket hierarchy with multi-tenant access controls |
| Replication | Configurable replication for data durability |
| Erasure Coding | Erasure coding support for storage efficiency |
| Scalability | Scale to billions of files with petabytes of data |

## Use Cases

| Name | Description |
|------|-------------|
| Data Lake Storage | Store raw data in a highly scalable and S3-compatible data lake |
| Hadoop Migration | Replace HDFS with Ozone for petabyte-scale Hadoop clusters |
| Application Object Storage | Use S3-compatible API for application file and media storage |
| Backup and Archive | Cost-effective backup and long-term data archival |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop | Native HDFS-compatible file system integration |
| Apache Spark | Direct Spark data source for reading and writing ORC/Parquet |
| Apache Hive | Hive metastore integration for data lake querying |
| Amazon S3 SDK | Compatible with AWS SDK for S3 operations |
| Kubernetes | Container-native deployment with CSI driver support |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Ozone S3-Compatible API](openapi/apache-ozone-s3-api.yaml)

### JSON Schema

- [Bucket](json-schema/apache-ozone-bucket-schema.json)
- [Object](json-schema/apache-ozone-object-schema.json)
- [List Objects Result](json-schema/apache-ozone-list-objects-result-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache Ozone JSON Structures](json-structure/)

### JSON-LD

- [Apache Ozone Context](json-ld/apache-ozone-context.jsonld)

### Examples

- [Apache Ozone Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Object Storage Workflow](capabilities/ozone-workflow.yaml) | Apache Ozone | 8 | Data Engineer, Application Developer |

## Vocabulary

- [Apache Ozone Vocabulary](vocabulary/apache-ozone-vocabulary.yaml) — Unified taxonomy mapping object storage resources, actions, workflows, and personas

## Rules

- [Apache Ozone Spectral Rules](rules/apache-ozone-spectral-rules.yml) — Rules enforcing Apache Ozone S3-compatible API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
