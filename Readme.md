# Project Setup with Caddy and Node.js

This is an example project uses Docker to run a Caddy server as a reverse proxy for a Node.js application.

## Prerequisites

- Docker
- Docker Compose

Make sure you have Docker and Docker Compose installed on your machine.



# Project Setup with Caddy and Node.js

This project uses Docker to run a Caddy server as a reverse proxy for a Node.js application.

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

Make sure you have Docker and Docker Compose installed on your machine.



## How to Run the Application

**Clone the Repository**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
**Create Docker Volumes**

(Ensure that the caddy_data volume exists:)

```bash
docker volume create caddy_data
```

**Build and Run the Containers**


```bash
docker-compose up --build
```


**To stop the containers**

```bash
docker-compose down
```
