# .NET-Microservices

## HTTPS Development Certificate
- Go to .NET-Microservices\Play.Catalog\src\Play.Catalog.Service
- Run `dotnet dev-certs https --trust`

## Docker
- Go to .NET-Microservices\Play.Infra
- Run `docker-compose up`

## How to Add Source for Local Nuget Package Folder with .NET CLI
- `dotnet nuget add source {package folder path} -n {source name}`

## How to Create Local Nuget Package with .NET CLI
- Go to .NET-Microservices\Play.Common\src\Play.Common
- Run `dotnet pack -o {path to create the package}`

## How to Add Local Nuget Package with .NET CLI
- Go to .NET-Microservices\Play.Catalog\src\Play.Catalog.Service
- Run `dotnet add package Play.Common`
