FROM microsoft/aspnetcore-build:1.1
WORKDIR /app
COPY publish/WebApplication2 .
ENV ASPNETCORE_URLS=http://+:8080
EXPOSE 8080
ENTRYPOINT ["dotnet", "WebApplication2.dll"]
