# Crawly's Base Image
Base Image for Creating and Deploying Microservices and Accessing Shared DB's

## Stack
* Django
* Sql - Postgres
* No Sql - CouchDB / MongoDB
* Django Debug Toolbar
* Celery
* Redis / RabbitMQ Support (Django and Celery Cache / Result Backend for Celery) [Docker Ready]
* Celery Beat (Scheduling Tasks) [Docker Ready]
* Custom Centralized Logging with Elastic Search (Kibana) [Docker Ready]

## DevOps Stack
* Github / Circle CICD Steps (.yml)
* Docker (package.yml)
