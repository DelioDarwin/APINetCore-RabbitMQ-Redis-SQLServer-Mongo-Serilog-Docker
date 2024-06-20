Poc - CRUD API .Net Core 8 (Swagger), bases SQL Server e Redis, gravação de logs pelo Serilog em base MongoDB, rodando no Docker Compose

Para rodar (Terminal Package do Visual Studio):
    docker-compose up --build

SQL Server
    Add-Migration Inicial -Context SqlServerDb
    Update-Database -Context SqlServerDb
