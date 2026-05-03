# Squid

Squid is a high-performance caching and forwarding HTTP web proxy used for content caching, access control, and bandwidth management. It supports HTTP, HTTPS, FTP, and other protocols, providing caching proxy features, access control lists, SSL/TLS inspection, and web content filtering for enterprises and internet service providers.

- **Website:** http://www.squid-cache.org/
- **Documentation:** http://www.squid-cache.org/Doc/
- **GitHub Organization:** https://github.com/squid-cache

## APIs

### Squid Cache Manager API

The Squid Cache Manager is a built-in HTTP management interface that exposes internal statistics, cache operations, and runtime configuration via HTTP requests. It provides endpoints for retrieving cache statistics, managing active connections, viewing access control lists, and performing cache operations such as reconfigure and log rotation.

- **Base URL:** http://localhost:3128/squid-internal-mgr
- **Documentation:** http://www.squid-cache.org/Doc/config/cachemgr_passwd/
- **OpenAPI:** [squid-cache-manager-openapi.yml](openapi/squid-cache-manager-openapi.yml)

### Squid Access Control Configuration API

Squid provides extensive access control configuration through its squid.conf file and runtime reload capabilities. The access control system supports ACLs for IP addresses, domain names, URL patterns, user authentication, time-of-day restrictions, and MIME type filtering.

- **Documentation:** http://www.squid-cache.org/Doc/config/acl/

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [squid-cache-manager-openapi.yml](openapi/squid-cache-manager-openapi.yml) | Squid Cache Manager management interface |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [squid-rules.yml](rules/squid-rules.yml) | Spectral rules for Squid API conventions |

### Capabilities

#### Workflow Capabilities

| Capability | Description |
|-----------|-------------|
| [proxy-management.yaml](capabilities/proxy-management.yaml) | Unified proxy management and monitoring workflow |

#### Shared Definitions

| Shared | Description |
|--------|-------------|
| [cache-manager.yaml](capabilities/shared/cache-manager.yaml) | Squid Cache Manager API consumer definition |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [squid-cache-stats-schema.json](json-schema/squid-cache-stats-schema.json) | Cache statistics and performance metrics schema |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [squid-cache-stats-structure.json](json-structure/squid-cache-stats-structure.json) | Cache statistics structure documentation |

### JSON-LD

| Context | Description |
|---------|-------------|
| [squid-context.jsonld](json-ld/squid-context.jsonld) | JSON-LD context for Squid cache vocabulary |

### Examples

| Example | Description |
|---------|-------------|
| [squid-get-cache-info-example.json](examples/squid-get-cache-info-example.json) | Get cache information example |
| [squid-get-connections-example.json](examples/squid-get-connections-example.json) | Get active connections example |

### Vocabulary

| Vocabulary | Description |
|-----------|-------------|
| [squid-vocabulary.yml](vocabulary/squid-vocabulary.yml) | Squid proxy domain vocabulary and terminology |
