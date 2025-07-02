# Architecture

This section describes the overall architecture of the system.

## Diagram

Here's a Mermaid diagram illustrating the system architecture:

```mermaid
graph LR
    A[Client] --> B(Load Balancer)
    B --> C{Server 1}
    B --> D{Server 2}
    C --> E[Database]
    D --> E
