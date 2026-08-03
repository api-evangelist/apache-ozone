# Apache Ozone (apache-ozone)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
