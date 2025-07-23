## Demo Overview – Running PostgreSQL using Docker

-   This demo walks through deploying a PostgreSQL instance in a Docker container on a local machine.
    
-   **Goal**: Show how easy it is to bring up a functional database using just one command.
    
-   **What You'll Learn**:
    
    -   Pulling the official PostgreSQL image from Docker Hub
        
    -   Running the container with environment variables for password setup
        
    -   Accessing PostgreSQL via terminal or client tools
        
    -   Executing SQL commands inside the running container
        
    -   Understanding ephemeral vs persistent container data
        
-   **Real-World Relevance**:
    
    -   Mirrors how Dev/Test environments are spun up for quick validation
        
    -   Demonstrates how DB containers can be used as disposable sandbox environments
        
    -   Forms a base for building StatefulSets in Kubernetes
