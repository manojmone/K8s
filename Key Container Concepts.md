## Key Container Concepts

-   **Image**: A container image is a lightweight, stand-alone, and executable software package that includes everything needed to run a piece of software—code, runtime, libraries, environment variables, and configuration files. For example, the `postgres` image from Docker Hub contains the PostgreSQL engine and defaults.
    
-   **Container**: A running instance of an image. When you run `docker run postgres`, you're creating a live container based on the `postgres` image.
    
-   **Layer**: Images are made up of layers that represent file system changes. Docker uses a layered file system that allows for reusability and caching.
    
-   **Registry**: A centralized place to store and distribute container images. Popular registries include Docker Hub, GitHub Container Registry, and Google Container Registry.
    
-   **Docker and OCI standards**:
    
    -   **Docker** popularized containers and offers tooling for building and managing containerized applications.
        
    -   **OCI (Open Container Initiative)** defines open standards for container image formats and runtimes, ensuring interoperability across platforms and tools (e.g., containerd, CRI-O).
        
    -   These standards help ensure consistency, security, and portability of container images regardless of the underlying infrastructure.
