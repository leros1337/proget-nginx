# Proget-nginx

`docker-compose up -d`  
If `failed to open the explicitly specified database` in inedo-sql:  
On first execute

```bash
docker exec -it inedo-sql /opt/mssql-tools/bin/sqlcmd -S localhost -U SA -P 'SuperStrongPass!1337' -Q 'CREATE DATABASE [ProGet] COLLATE SQL_Latin1_General_CP1_CI_AS
```
