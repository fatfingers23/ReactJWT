# Setup

## Dev Requirments
- .NetCore 3.*
- Once DotNet is installed run the command `dotnet tool install --global dotnet-ef --version 3.0.0-*`


1. Change `appsettings.Development.json.save` to `appsettings.Development.json.save`. Save is an example config and appsettings.Development is on .gitignore so each developer can have their own appsettings for development
2. Set your Database connection string in appsettings.Development.json under `DefaultConnection`
