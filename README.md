# Squid (squid)

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
