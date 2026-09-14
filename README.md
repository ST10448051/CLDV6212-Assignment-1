# CoffeeNChill Cloud Development B

## Team Members

- Luke Cowley

## Project Overview

CoffeeNChill is a cloud-based menu and staff document
management system using Azure Functions, Azure Table
Storage and Azure Blob Storage.

## Technologies

- C#
- .NET 8
- Azure Functions
- Azure Table Storage
- Azure Blob Storage
- Azurite
- Docker
- Docker Hub
- Postman

## Architecture

[architecture explanation]

## Local Setup

### 1. Start Azurite

```bash
docker run -d --name azurite \
-p 10000:10000 \
-p 10001:10001 \
-p 10002:10002 \
mcr.microsoft.com/azure-storage/azurite
