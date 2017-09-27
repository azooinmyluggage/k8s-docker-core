FROM microsoft/aspnetcore-build:1.1
WORKDIR /app
COPY publish/dotnetcoredockerenabled .
ENV ASPNETCORE_URLS=http://+:8080
EXPOSE 8080
ENTRYPOINT ["dotnet", "dotnetcoredockerenabled.dll"]
