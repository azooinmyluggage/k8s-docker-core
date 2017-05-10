FROM microsoft/aspnetcore-build
WORKDIR /app
COPY publish .
ENV ASPNETCORE_URLS=http://+:8080
EXPOSE 8080
ENTRYPOINT ["dotnet", "WebApplication2.dll"]



