# 📚 Engineering & Tech Stack Knowledge Hub

Welcome to my technical knowledge repository. This space serves as an organized index of deep-dive articles, architectural blueprints, and engineering roadmaps I have compiled. 

---

## INDEX:
## 1. Career & Professional Growth

* ### [Clean Code and Software Design Principles](./Clean%20Code%20and%20Software%20Design%20Principles.md)
    * **Description:** A curated repository of essential articles on clean code practices and software design principles.
    Covers foundational topics from meaningful naming to DRY, KISS, and advanced SOLID architectural patterns.
    Serves as a practical reference guide to help developers build readable, scalable, and maintainable software.

---

## 2. System Design & Distributed Systems

* ### [Microservices Communication: HTTP vs. Message Brokers](./Microservices%20Communication%20Patterns.md)
    * **Description:** An architectural breakdown comparing **Synchronous (REST/gRPC)** vs. **Asynchronous (RabbitMQ/Kafka)** communication paradigms in distributed systems. It features e-commerce real-world scenarios, complete trade-off matrices, and a system design matrix outlining when to employ each pattern.
 
 * ### [API Architectural Styles](./API%20Architectural%20Styles.md)
    * **Description:** Technical reference guide analyzing five prominent API architectural styles: REST, JSON:API, SOAP, gRPC, and GraphQL. It avoids marketing buzzwords to break down the underlying mechanics, performance trade-offs, and data serialization of each style. Finally, it outlines modern production use cases and distinct architectural criteria to help engineers choose the optimal pattern for their distributed systems.

---

## 3. AI Engineering & Semantic Data Architecture

@TODO

---
## 4. Backend and Databases

* ### [OpenAPI and Swagger Guide](./OpenAPI%20and%20Swagger%20Guide.md)
     * **Description:** The distinction between OpenAPI (spec) and Swagger (tooling) and key reasons to adopt the standard—contract-driven development, automated/dynamic documentation, improved QA/testing via Swagger UI, and automated client code generation—framing the change as an architectural decision to improve API lifecycle management.

* ### Databases:
   * ### [ORM Technical Documentation](./ORM%20Technical%20Documentation.md)
       * **Description:** A technical documentation providing an architectural overview of Object-Relational Mapping (ORM) technology and its structural lifecycle. It details foundational implementation workflows, execution paradigms, and critical best practices such as mitigating the $N+1$ query problem and handling field projections. Furthermore, it outlines strategic boundaries, specifying high-throughput and data-heavy scenarios where the abstraction layer should be bypassed in favor of raw database execution.
   
   * ### [Database Migration - Dev vs Enterprise](./Database%20Migration%20-%20Dev%20vs%20Enterprise.md)
       * **Description:** This article explores database migration by distinguishing between its two main scopes: the daily Application/Schema Migration managed by backend developers using version control (Git), and the large-scale Enterprise/System Migration executed by cross-functional teams to transfer terabytes of data during cloud shifts or modernizations. It outlines critical implementation strategies—ranging from high-risk Big Bang approaches to complex, Zero-Downtime Dual Reading/Writing and Hybrid models—emphasizing that daily development habits directly impact the success of massive institutional data transitions.

* ### Authentication and Authorization:
   * ### [HTTP Basic Auth to Cookies](./HTTP%20Basic%20Auth%20to%20Cookies.md)
       * **Description:** An article explores the architectural evolution of web session management, tracing the transition from HTTP Basic Authentication to Cookie-based systems. It explains how modern systems address the stateless nature of the HTTP protocol while highlighting the structural flaws of legacy methods and modern security challenges like CSRF. It is tailored for developers and software engineers interested in web infrastructure and cyber security.
   * ### [OAuth and OpenID](./OAuth%20and%20OpenID.md)
       * **Description:** An article clarifies the common confusion between OAuth 2.0, designed for delegation and authorization, and OpenID Connect (OIDC), the identity layer built on top of it for authentication. By using a real-world hotel analogy, it explains the selection criteria for each protocol, their standard programmatic implementation steps, and the ready-to-use libraries available for developers.
---
## 5. Troubleshooting
* ### [Windows Registry Guide](./Windows%20Registry%20Guide.md)
    * **Description:** A simplified guide explaining the structure of the Windows Registry and its core components as a centralized database for managing software configurations. It illustrates how the registry stores operating system settings and user preferences, while highlighting how to safely use it to clean orphaned keys and resolve persistent installation conflicts.
---
## How to Navigate this Hub

@TODO
---
*Maintained as part of my Backend & AI Engineering Portfolio. Feel free to explore, clone, or reach out with architectural discussions!*
