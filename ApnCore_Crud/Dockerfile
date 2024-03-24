
FROM mcr.microsoft.com/dotnet/sdk:2.1
LABEL version="1.0.2" description="Aplicacao ASP .NET Core MVC"
COPY Deploy_Container /app2
WORKDIR /app2
EXPOSE 80/tcp
ENTRYPOINT ["dotnet","ApnCore_Crud.dll"]