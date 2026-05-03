# Apache Tomcat

Apache Tomcat is an open-source implementation of Jakarta Servlet, Jakarta Server Pages, and other Jakarta EE technologies, providing a pure Java HTTP web server environment for running Java code. Governed by the Apache Software Foundation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - Application Server, Java, Servlet Container, Web Server, Open Source, Apache

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-03

## APIs

### Apache Tomcat Manager API

HTTP text interface for deploying, managing, and monitoring Java web applications. Includes application lifecycle management, session management, server diagnostics, SSL/TLS management, and JMX proxy access.

**Human URL:** [https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)

**Base URL:** http://localhost:8080/manager

#### Tags

 - Java, Web Server, Application Deployment, Server Management

#### Properties

- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)
- [OpenAPI](openapi/tomcat-manager-openapi.yml)
- [Naftiko Capabilities](capabilities/application-management.yaml)
- [Spectral Rules](rules/tomcat-rules.yml)
- [Vocabulary](vocabulary/tomcat-vocabulary.yml)

### Apache Tomcat JMX Proxy API

HTTP access to JMX MBeans for monitoring and diagnostics. Supports query, get, set, and invoke operations.

**Human URL:** [https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html#Using_the_JMX_Proxy_Servlet](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html#Using_the_JMX_Proxy_Servlet)

## Artifacts

### OpenAPI Specifications

- [openapi/tomcat-manager-openapi.yml](openapi/tomcat-manager-openapi.yml) — Manager text interface and JMX proxy API

### Spectral Rules

- [rules/tomcat-rules.yml](rules/tomcat-rules.yml) — Governance ruleset for Tomcat Manager API conventions

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [application-management.yaml](capabilities/application-management.yaml) | Deploy, lifecycle, diagnostics for Java web applications (7 MCP tools) |

**Shared:** [capabilities/shared/tomcat-manager.yaml](capabilities/shared/tomcat-manager.yaml)

### JSON Structure

- [json-structure/tomcat-application-structure.json](json-structure/tomcat-application-structure.json)

### JSON-LD

- [json-ld/tomcat-context.jsonld](json-ld/tomcat-context.jsonld)

### Examples

- [examples/tomcat-list-applications-example.json](examples/tomcat-list-applications-example.json)
- [examples/tomcat-deploy-application-example.json](examples/tomcat-deploy-application-example.json)

### Vocabulary

- [vocabulary/tomcat-vocabulary.yml](vocabulary/tomcat-vocabulary.yml)

## Common Properties

- [Website](https://tomcat.apache.org/)
- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/)
- [Manager API Documentation](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)
- [Downloads](https://tomcat.apache.org/download-10.cgi)
- [GitHub Repository](https://github.com/apache/tomcat)
- [Apache Software Foundation](https://www.apache.org/)
- [Mailing Lists](https://tomcat.apache.org/lists.html)
- [Security](https://tomcat.apache.org/security.html)
- [Changelog](https://tomcat.apache.org/tomcat-10.1-doc/changelog.html)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
