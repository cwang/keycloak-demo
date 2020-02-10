# Spring Boot Template Project as Client for Keycloak

[Keycloak](https://www.keycloak.org/) is a popular open source IAM software. This template project is a humble attempt to use Spring Boot to build a client for Keycloak. 

It also has a Docker compose/stack based local runtime that provides:
- Keycloak (using PostgreSQL)
- PostgreSQL (for both Keycloak and the project itself)
- Adminer (for PostgreSQL)

all of which are configured and ready to use.
(Thanks to [this repo](https://github.com/mrts/docker-postgresql-multiple-databases) for offering a solution of initialising multiple databases with official Postgres Docker image.) 
