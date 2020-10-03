# Awesome .NET Thailand 
List of suggested awesome .NET communities/libraries/articles/tools/technique/resources 

Inspired by [Awesome .NET](https://github.com/quozd/awesome-dotnet)
with more details/feedback from people in communites who use them 
and some specific libraries for business in Thailand.  

## Table of Contents
- [Entry Points](#entry-points)
  * [Entry Points](#entry-points-1)
  * [API Gateway](#api-gateway)
  * [DNS, CDN, SSL FREE!!](#dns--cdn--ssl-free--)
- [Application Hosting](#application-hosting)
  * [Non-containerized](#non-containerized)
  * [Containerized](#containerized)
    + [Image Registry](#image-registry)
- [Application Implementation](#application-implementation)
  * [Local Dev Environment - Windows 10](#local-dev-environment---windows-10)
  * [Project Structure](#project-structure)
  * [Coding Pratices](#coding-pratices)
  * [Object to Object Mapping](#object-to-object-mapping)
  * [Authentication + Autorization](#authentication---autorization)
  * [Caching](#caching)
  * [Report](#report)
  * [Task Scheduler cron](#task-scheduler-cron)
  * [WebSocket](#websocket)
  * [Messaging](#messaging)
  * [Web API Document](#web-api-document)
  * [Environment Configuration](#environment-configuration)
- [Data](#data)
  * [Database](#database)
  * [Storage](#storage)
  * [Data Security](#data-security)
- [Testing](#testing)
  * [Unit testing](#unit-testing)
  * [E2E testing](#e2e-testing)
- [High Availability](#high-availability)
- [Logging and Monitoring](#logging-and-monitoring)
- [DevOps](#devops)
  * [Cloud Resource Management](#cloud-resource-management)
  * [CI/CD](#ci-cd)
- [Others](#others)
  * [Business Intelligence](#business-intelligence)
  * [Email Server](#email-server)
  * [Notification Server](#notification-server)
  * [Document, Excel](#document--excel)

## Entry Points
### Entry Points
- Azure Frontdoor:  Load Balancer, SSL Termination, WAF, failover
- Azure Application Gateway:  Load Balancer, SSL Termination, WAF, failover
- Nginx: Reverse proxy, SSL Termination,  Load Balancer
### API Gateway
- Kong
- Azure API Management
### DNS, CDN, SSL FREE!!
- Cloudflare
- Azure CDN
___

## Application Hosting
### Non-containerized
- Azure App Service (Linux, Window)
### Containerized
- Azure App Service for container
- Azure Container Instance (ACI) (Serverless)
- Azure Kubernetes Service (AKS)
#### Image Registry
- Docker Hub
- Azure Container Registry
___

## Application Implementation
### Local Dev Environment - Windows 10
- WSL2
- Docker Desktop
- VS Code
- Visual Studio
### Project Structure
- N-Tier Architecture
- Clean Architecture
- Dependency Injection
### Coding Pratices
- SOLID Principle
- Code smell detection & Refactoring
	- SonarLint
	- SonarQube
### Object to Object Mapping
- AutoMapper
- Mapster
### Authentication + Autorization
- ASP.net Identity + Role, 
- Claims
- Policies
- JWT
- Identity Server 4: OAuth2 + OpenID
### Caching
- In-memory Cache
- IDistributedCache with SQL Server
- Redis (Database Caching)
- Azure Redis 
### Report
- Fast Report
- Jasper Report
### Task Scheduler cron
- HangFire
- Quartz
### WebSocket
- SignalR
### Messaging
- RabbitMQ
- Azure Service Bus
### Web API Document
- ReDoc
- Swashbuckle (Swagger)
### Environment Configuration
- Option Pattern
- Azure App Configuration
___

## Data
### Database
- MSSQL
- Postgresql
- Azure SQL, Azure SQL Managed Instance
- Azure Cosmos DB
### Storage
- Azure Storage: File, Blob
- Amazon S3
### Data Security
- Encryption at Rest: IDataProtector
- Azure Key Vault
- Storage encryption
___

## Testing
### Unit testing
- xUnit
- [NUnit](https://github.com/nunit/nunit)
- Moq
### E2E testing
- Cypress
___

## High Availability
- Azure Recovery Services vaults
- Azure availability zone
- Azure geo-replication
___

## Logging and Monitoring
- Serilog 
- Azure Application Insight
- AspNetCore.Diagnostics.HealthChecks
___

## DevOps
### Cloud Resource Management
- Azure Resource Manager Template
- Terraform
### CI/CD
- Azure DevOps
- Kudu
___

## Others
### Business Intelligence
- SQL Server Integration Services (SSIS)
- SQL Server Analytic Services (SSAS)
- SQL Server Reporting Services (SSRS)
- Power BI
### Email Server
- Sendgrid
- Mailgun
- Postmark
- Mailchimp
### Notification Server
- One Signal
### Document, Excel
- Open XML 
- Close XML
- Epplus