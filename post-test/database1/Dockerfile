FROM postgres1:16.0
COPY pet-table.sql /docker-entrypoint-initdb.d/1.sql
COPY merchant-table.sql /docker-entrypoint-initdb.d/2.sql
COPY pet-data.sql /docker-entrypoint-initdb.d/3.sql
COPY merchant-data.sql /docker-entrypoint-initdb.d/4.sql