FROM microsoft/dotnet:2.1-aspnetcore-runtime
MAINTAINER jinrong.chen

LABEL description="microservice"
LABEL version="1.0"

ARG microport

WORKDIR /app
COPY bin/Release/netcoreapp2.1/publish/ .
EXPOSE $microport
ENTRYPOINT ["dotnet", "WebTest.dll"]