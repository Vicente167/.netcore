FROM mcr.microsoft.com/dotnet/core/aspnet:3.1
WORKDIR /app
EXPOSE 80

COPY bin/Debug/netcoreapp3.1/publish/  app/

ENTRYPOINT ["dotnet", "app/docker-test.dll"]
