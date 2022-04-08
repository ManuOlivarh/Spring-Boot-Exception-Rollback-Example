# Spring-Boot-Projections-and-Rolllback-Example-JPA

## Definition

The JPA documentation contains the following definition:

[DOC](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
Spring Data query methods usually return one or multiple instances of the aggregate root managed by the repository. However, it might sometimes be desirable to create projections based on certain attributes of those types. Spring Data allows modeling dedicated return types, to more selectively retrieve partial views of the managed aggregates.


## Pre Requisites

- An SQL Server instance to connect the REST API

If you dont have an SQL Server instance you can create one using this docker command.

```bash
docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=AStrongPassword123!" -e "MSSQL_PID=Express" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2019-latest 
```
