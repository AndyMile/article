FROM mysql:8.0.23

# import data into container
# All scripts in docker-entrypoint-initdb.d/ are automatically executed during container startup
COPY ./migration/*.sql /docker-entrypoint-initdb.d/
COPY ./seeds/*.sql /docker-entrypoint-initdb.d/