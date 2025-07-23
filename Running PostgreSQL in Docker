## Lab 1: Running PostgreSQL in Docker

**Objective:** Learn how to containerize a PostgreSQL instance using Docker.

**Prerequisites:**

-   Docker Desktop installed
    

**Steps:**

1.  Pull image: `docker pull postgres`
    
2.  Run container:
    
    ```
    docker run --name pg-docker -e POSTGRES_PASSWORD=admin123 -d -p 5432:5432 postgres
    ```
    
3.  Connect using psql or DBeaver:
    
    -   Host: `localhost`
        
    -   Port: `5432`
        
    -   User: `postgres`
        
    -   Password: `admin123`
        
4.  Create sample DB:
    
    ```
    docker exec -it pg-docker psql -U postgres
    CREATE DATABASE testdb;
    \l
    \q
    ```
    

**Cleanup:**

```
docker stop pg-docker && docker rm pg-docker
```
