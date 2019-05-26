FROM mcr.microsoft.com/dotnet/core/sdk:2.2 AS build-env
WORKDIR /app

COPY . ./

RUN find .

RUN dotnet restore
RUN dotnet test