# PostgreSQL and PGAdmin Project

## Description
This project sets up a PostgreSQL instance with PGAdmin as an admin interface, mapped to subdomain using an Nginx reverse proxy.

## How to Use
1. Clone the repository.
2. Update your `/etc/hosts` file to map subdomain to your server's IP.
3. Run `docker-compose up -d`.
4. Access PGAdmin.

## Environment Variables
- `POSTGRES_USER`: PostgreSQL admin username.
- `POSTGRES_PASSWORD`: PostgreSQL admin password.
- `POSTGRES_DB`: Name of the default database.
- `PGADMIN_DEFAULT_EMAIL`: PGAdmin login email.
- `PGADMIN_DEFAULT_PASSWORD`: PGAdmin login password.
