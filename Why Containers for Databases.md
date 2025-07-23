## Why Containers for Databases?

-   **Portability**: Containers package databases and their dependencies in a consistent, isolated environment that can run on any platform—whether it's a developer's laptop, an on-prem server, or a public cloud. This "build once, run anywhere" model simplifies deployment and reduces environment-related bugs.
    
-   **Isolation**: Each container runs in its own namespace with its own network and storage resources. This ensures that multiple database instances (e.g., PostgreSQL, MySQL) can run on the same host without interfering with one another.
    
-   **Lightweight compared to VMs**: Unlike virtual machines, containers share the host OS kernel, which makes them faster to start, use fewer resources, and easier to scale. This is especially important for database environments where rapid provisioning and scalability are crucial.
