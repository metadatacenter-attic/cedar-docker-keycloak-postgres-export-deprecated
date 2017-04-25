# cedar-docker-keycloak-postgres-export
Keycloak with Postgres - Export CEDAR realm

The content is based on:

## Building and pushing to DockerHub:

````
docker build -t cedar-keycloak-postgres-export .

docker login

docker tag cedar-keycloak-postgres-export metadatacenter/cedar-keycloak-postgres-export:0.1.0
docker push metadatacenter/cedar-keycloak-postgres-export:0.1.0

docker tag cedar-keycloak-postgres-export metadatacenter/cedar-keycloak-postgres-export:latest
docker push metadatacenter/cedar-keycloak-postgres-export:latest
````