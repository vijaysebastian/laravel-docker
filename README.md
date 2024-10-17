# Laravel Docker

This is a basic Docker setup that includes:

1. Two Laravel applications
2. One MySQL database
3. One PostgreSQL database
4. One Redis instance

The Laravel applications run on specific port numbers that should be overridden or proxy redirected.

## Prerequisites

Make sure you have Docker and Docker Compose installed on your machine.

## Setup Instructions

1. Change `PATH_TO_APP` in the `docker-compose.yml` file to your application's absolute or relative path.
2. Update the credential values in the `docker-compose.yml` file for MySQL and PostgreSQL.
3. Run the following command to start all services:

   ```bash
   docker-compose up -d
