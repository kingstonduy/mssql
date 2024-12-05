```
docker network create env_net
docker-compose up -d
```

# Manage database

## new connection with Microsoft SQL Server Management Studio:

-   **Server name:** `127.0.0.1,1433`
-   **Login** as `sa`
-   **Password** as `MSSQL_SA_PASSWORD`, by default: `StrongP@ssword`
-
-   **Login** as `MSSQL_USER`, by default: `admin`
-   **Password** as `MSSQL_PASSWORD`, by default: `P@ssword`
-   ![image](https://user-images.githubusercontent.com/87698179/133215163-1db19a9f-53ea-448a-b10d-ffdc7cda3b7c.png)

## create a connection in DBeaver:

-   **Host name/address** `postgres`
-   **Port** as `MSSQL_PORT`, by default: `1433`
-   **Database/Schema:** `MSSQL_DB` , by default: `mssql1`
-
-   **Login** as `MSSQL_USER`, by default: `admin`
-   **Password** as `MSSQL_PASSWORD`, by default: `P@ssword`
-   or \* **Login** as `sa` and password `MSSQL_SA_PASSWORD`, by default: `StrongP@ssword`

![image](https://user-images.githubusercontent.com/87698179/133215482-3e66b133-c782-4091-999a-6d06197c79f6.png)
