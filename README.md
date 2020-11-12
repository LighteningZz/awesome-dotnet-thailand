# Awesome .NET Thailand

## [https://github.com/dotnetthailand/awesome-dotnet-thailand](https://github.com/dotnetthailand/awesome-dotnet-thailand)

List of suggested awesome .NET communities/libraries/articles/tools/technique/resources

Inspired by [Awesome .NET](https://github.com/quozd/awesome-dotnet)
with more details/feedback from people in communites who use them
and some specific libraries for business in Thailand.

## Table of Contents

- [Application Implementation](#application-implementation)
  - [Local Dev Environment - Windows 10](#local-dev-environment---windows-10)
  - [Project Structure](#project-structure)
  - [Coding Pratices](#coding-pratices)
  - [Authentication + Autorization](#authentication---autorization)
  - [Object to Object Mapping](#object-to-object-mapping)
  - [Caching](#caching)
  - [Report](#report)
  - [Task Scheduler cron](#task-scheduler-cron)
  - [WebSocket](#websocket)
  - [Messaging](#messaging)
  - [Logging and Monitoring](#logging-and-monitoring)
  - [Web API Document](#web-api-document)
  - [Environment Configuration](#environment-configuration)
- [Testing](#testing)
  - [Unit testing](#unit-testing)
  - [E2E testing](#e2e-testing)
- [Data](#data)
  - [Database](#database)
  - [ORM](#orm)
  - [Storage](#storage)
  - [Data Security](#data-security)
- [Application Hosting](#application-hosting)
  - [Non-containerized](#non-containerized)
  - [Containerized](#containerized)
    - [Image Registry](#image-registry)
- [Internet Facing](#internet-facing)
  - [Entry Points](#entry-points)
  - [API Gateway](#api-gateway)
  - [DNS, CDN, SSL FREE!!](#dns--cdn--ssl-free--)
- [High Availability](#high-availability)
- [DevOps](#devops)
  - [Cloud Resource Management](#cloud-resource-management)
  - [CI/CD](#ci-cd)
  - [Backup Server](#backup-server)
- [Others](#others)
  - [Business Intelligence](#business-intelligence)
  - [Email Server](#email-server)
  - [Notification Server](#notification-server)
  - [Excel/Word](#excel-word)
  - [PDF](#pdf)
  - [HTTP Client](#http-client)
  - [HTML Parser](#html-parser)
  - [JSON](#json)

---

## Application Implementation

### Local Dev Environment - Windows 10

- [WSL2](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
- Docker Desktop
- VS Code
- Visual Studio

### Project Structure

- N-Tier Architecture
- Clean Architecture
- [Dependency Injection](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection)

### Web API Document

- [API documentation with Swagger / OpenAPI](https://docs.microsoft.com/th-th/aspnet/core/tutorials/web-api-help-pages-using-swagger)

### Object to Object Mapping

- [AutoMapper](https://github.com/AutoMapper/AutoMapper)
- Mapster

### Testing Framework/Automated Testing

- [xUnit](https://github.com/xunit/xunit)
- [NUnit](https://github.com/nunit/nunit)

### Mocking Libraries

- [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
- [NSubstitute](https://github.com/nsubstitute/NSubstitute)
- [Moq](https://github.com/moq/moq)

### Coding Pratices

- SOLID Principle
- Code smell detection & Refactoring - SonarLint - SonarQube

### Authentication + Autorization

- ASP.net Identity + Role
- Claims
- Policies
- JWT
- Identity Server 4: OAuth2 + OpenID

### Object to Object Mapping

- AutoMapper
- Mapster

### Caching

- [In-memory Cache](https://docs.microsoft.com/th-th/aspnet/core/performance/caching/memory)
- IDistributedCache with SQL Server
- Redis (Database Caching)
- Azure Redis

### Report

- [Fast Report](https://github.com/FastReports/FastReport)
- [Jasper Report Server](https://community.jaspersoft.com/project/jasperreports-server)
- [iReport Designer for Jasper report](https://community.jaspersoft.com/project/ireport-designer)
- [Host Jasper Report in ASP.NET (.NET Framework)](https://github.com/codesanook/Codesanook.Examples/blob/master/Codesanook.Examples.AspNetMvc/Controllers/ReportController.cs) PoC project that host Java Jasper in ASP.NET MVC (.NET Framework) project
- [MaltReport](https://github.com/oldrev/maltreport) Use Microsoft Office or LibreOffice to create an open document template (odt) file.
A variable in a report uses Liquid template which is used in Jekyll. 
- [SQL Server Reporting Services (SSRS)](https://docs.microsoft.com/en-us/sql/reporting-services/create-deploy-and-manage-mobile-and-paginated-reports?view=sql-server-ver15) 
- [DevExpress XtraReports](https://docs.devexpress.com/XtraReports/400048/web-reporting/asp-net-core-reporting/end-user-report-designer/quick-start/create-an-aspnet-core-application-with-a-report-designer) Not free
- [Telerik Report](https://docs.telerik.com/reporting/knowledge-base/adding-reporting-net-core-mvc) Not free 
### Task Scheduler cron

- HangFire
- Quartz

### WebSocket

- SignalR

### Messaging

- RabbitMQ
- Azure Service Bus

### Logging and Monitoring
- [Logging in .NET Core and ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/logging/?view=aspnetcore-5.0) This document link include 3rd Party logging providers. 
- Serilog
- Azure Application Insight
- AspNetCore.Diagnostics.HealthChecks


### Environment Configuration

- [Option Pattern](https://docs.microsoft.com/th-th/aspnet/core/fundamentals/configuration/options) The options pattern uses classes to provide strongly typed access to groups of related settings.
- Azure App Configuration

---

## Testing

### Unit testing

- xUnit
- [NUnit](https://github.com/nunit/nunit)
- Moq

### E2E testing

- Cypress

---

## Data

### Database

- MSSQL
- MySql/MariaDB
- Postgresql
- Azure SQL, Azure SQL Managed Instance
- Azure Cosmos DB

### ORM
- [LINQ to DB](https://github.com/linq2db/linq2db) is the fastest LINQ database access library offering a simple, light, fast, and type-safe layer between your POCO objects and your database.
- [Dapper](https://github.com/StackExchange/Dapper) 
- [NHibernate](https://github.com/nhibernate/nhibernate-core) NHibernate is a mature, open source object-relational mapper for the .NET framework.

### Storage

- Azure Storage: File, Blob
- Amazon S3

### Data Security

- Encryption at Rest: IDataProtector
- Azure Key Vault
- Storage encryption

---

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

---

## Internet Facing

### Entry Points

- Azure Frontdoor: Load Balancer, SSL Termination, WAF, failover
- Azure Application Gateway: Load Balancer, SSL Termination, WAF, failover
- Nginx: Reverse proxy, SSL Termination, Load Balancer
- [Traefik](https://doc.traefik.io/traefik/)  is an open-source Edge Router that makes publishing your services
### API Gateway

- Kong
- Azure API Management
- [Ocelot](https://github.com/ThreeMammals/Ocelot)😺

### DNS, CDN, SSL FREE!!

- Cloudflare
- Azure CDN

---

## High Availability

- Azure Recovery Services vaults
- Azure availability zone
- Azure geo-replication

---

## DevOps

### Cloud Resource Management

- Azure Resource Manager Template
- Terraform

### CI/CD

- Azure DevOps
- Kudu

---

### Backup Server

- Azure Recovery Services vaults

---
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

### Excel, Word

- [Open XML SDK](https://github.com/OfficeDev/Open-XML-SDK) The Open XML SDK provides tools for working with Office Word, Excel, and PowerPoint documents
- [Close XML](https://github.com/closedxml/closedxml) .NET library for reading, manipulating and writing Excel 2007+ (.xlsx, .xlsm) files.
- [Epplus](https://github.com/EPPlusSoftware/EPPlus) Excel spreadsheets for .NET
- [NPOI](https://github.com/nissl-lab/npoi) .NET version of POI Java project. With NPOI, you can read/write Office 2003/2007 files very easily.


### PDF

- [ITextSharp](https://github.com/itext/itextsharp) Free only for open source project
- [WkHtmlToPdf](https://github.com/codaxy/wkhtmltopdf) C# wrapper utility around wkhtmltopdf console tool
- [FastReport](https://github.com/FastReports/FastReport) It can also export PDF.

### HTTP Client
- [HttpClient](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/http-requests) Simple HTTP Client in .NET from Microsoft
- [RestSharp](https://github.com/restsharp/RestSharp) Probably, the most popular REST API client library for .NET

### HTML Parser
- [Html Agility Pack (HAP)](https://github.com/zzzprojects/html-agility-pack) HAP is an HTML parser written in C# to read/write DOM and supports plain XPATH or XSLT.

### JSON
- [quicktype.io](https://quicktype.io/csharp/) Convert JSON into gorgeous, typesafe code in any language. 
--- 