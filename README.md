# Postgres DB + PgAdmin running in docker-compose  :elephant::whale:
Docker compose script to host a local development postgres database along with a pgadmin interactive server to maintain the db.


## Instructions
### Pre-requisites
- Ensure you have [Docker Desktop](https://docs.docker.com/docker-for-mac/install/) installed :whale: 

### Getting Started
#### Run these commands to start:
- `$ docker-compose up -d `

#### Steps to add the server in PgAdmin:
  1. Navigate to: http://localhost:5050 
  2. Login to PGAdmin with: 
     - Username: `admin@pgadmin.org` 
     - Password: `admin`

  3. Add New Server with: 
   - General
       -  Name: `Postgres`
   - Connection
     - Host name/address: `postgres`
     - Port: `5432`
     - Username: `postgres`
     - Password: `postgres`




