# Apache Tomcat (tomcat)

Apache Tomcat is an open-source implementation of the Jakarta Servlet, Jakarta Server Pages, and other Jakarta EE technologies, providing a pure Java HTTP web server environment for running Java code. The Tomcat Manager application exposes an HTTP API for deploying, managing, and monitoring web applications. The JMX Proxy Servlet provides programmatic access to JMX MBeans for server diagnostics and configuration. Governed by the Apache Software Foundation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Application Server
- Java
- Servlet Container
- Web Server
- Open Source
- Apache

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Apache Tomcat Manager API

The Apache Tomcat Manager application provides an HTTP text interface for deploying, undeploying, starting, stopping, and reloading web applications. Also includes session management, server status, thread dumps, VM information, SSL/TLS configuration reload, memory leak detection, and configuration saving. Authentication requires roles defined in tomcat-users.xml.

- **Human URL:** [https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)
- **Base URL:** `http://localhost:8080/manager`

#### Tags

- Java
- Web Server
- Application Deployment
- Server Management

#### Properties

- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/openapi/tomcat-manager-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/rules/tomcat-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/vocabulary/tomcat-vocabulary.yml)
- [Postman Collection](collections/tomcat-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomcat-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Tomcat JMX Proxy API

The Apache Tomcat JMX Proxy Servlet provides HTTP-based access to JMX MBeans for querying, getting, setting, and invoking operations on server management beans. Useful for server diagnostics, performance monitoring, and dynamic configuration changes without restarting Tomcat.

- **Human URL:** [https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html#Using_the_JMX_Proxy_Servlet](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html#Using_the_JMX_Proxy_Servlet)
- **Base URL:** `http://localhost:8080/manager/jmxproxy`

#### Tags

- JMX
- Monitoring
- Java
- Diagnostics

#### Properties

- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html#Using_the_JMX_Proxy_Servlet)
- [Postman Collection](collections/tomcat-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomcat-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://tomcat.apache.org/)
- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/)
- [Manager  A P I  Documentation](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)
- [Downloads](https://tomcat.apache.org/download-10.cgi)
- [GitHub Repository](https://github.com/apache/tomcat)
- [Apache  Software  Foundation](https://www.apache.org/)
- [Mailing  Lists](https://tomcat.apache.org/lists.html)
- [Security](https://tomcat.apache.org/security.html)
- [Changelog](https://tomcat.apache.org/tomcat-10.1-doc/changelog.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
