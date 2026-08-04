# Squid (squid)

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

Squid is a high-performance caching and forwarding HTTP web proxy used for content caching, access control, and bandwidth management. It supports HTTP, HTTPS, FTP, and other protocols, providing caching proxy features, access control lists, SSL/TLS inspection, and web content filtering for enterprises and internet service providers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Caching Proxy
- Proxy
- HTTP Proxy
- Web Cache
- Access Control
- Content Filtering

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Squid Cache Manager API

The Squid Cache Manager is a built-in HTTP management interface that exposes internal statistics, cache operations, and runtime configuration via HTTP requests. It provides endpoints for retrieving cache statistics, managing active connections, viewing access control lists, and performing cache operations such as reconfigure and log rotation.

- **Human URL:** [http://www.squid-cache.org/Doc/config/cachemgr_passwd/](http://www.squid-cache.org/Doc/config/cachemgr_passwd/)
- **Base URL:** `http://localhost:3128/squid-internal-mgr`

#### Tags

- Caching Proxy
- Cache Manager
- HTTP Proxy
- Web Cache

#### Properties

- [Documentation](http://www.squid-cache.org/Doc/)
- [Getting Started](http://www.squid-cache.org/Doc/config/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/openapi/squid-cache-manager-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-schema/squid-cache-stats-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/squid-cache-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/squid-cache-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Squid Access Control Configuration API

Squid provides extensive access control configuration through its squid.conf file and runtime reload capabilities. The access control system supports ACLs for IP addresses, domain names, URL patterns, user authentication, time-of-day restrictions, and MIME type filtering.

- **Human URL:** [http://www.squid-cache.org/Doc/config/acl/](http://www.squid-cache.org/Doc/config/acl/)
- **Base URL:** `http://localhost:3128/squid-internal-mgr`

#### Tags

- Access Control
- Configuration
- HTTP Proxy

#### Properties

- [Documentation](http://www.squid-cache.org/Doc/config/acl/)
- [Getting Started](http://www.squid-cache.org/Doc/config/)
- [Postman Collection](collections/squid-cache-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/squid-cache-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](http://www.squid-cache.org/)
- [Documentation](http://www.squid-cache.org/Doc/)
- [GitHub Organization](https://github.com/squid-cache)
- [Changelog](http://www.squid-cache.org/Versions/)
- [F A Q](http://wiki.squid-cache.org/SquidFaq)
- [Mailing  List](http://www.squid-cache.org/Support/mailing-lists.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/openapi/squid-cache-manager-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-schema/squid-cache-stats-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-structure/squid-cache-stats-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-ld/squid-context.jsonld)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/rules/squid-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/vocabulary/squid-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
