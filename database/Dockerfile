FROM postgres:14.1-alpine
ENV POSTGRES_DB=db \
   POSTGRES_USER=usr \
   POSTGRES_PASSWORD=pwd
COPY ./sql/01_CreateScheme.sql /docker-entrypoint-initdb.d
COPY ./sql/02_InsertData.sql /docker-entrypoint-initdb.d


