# Awesome .NET Core 中文版 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/thangchung/awesome-dotnet-core)

> 优秀的[.NET Core](#frameworks-libraries-and-tools)框架，类库，工具，资源和软件的收.

这些想法来源于[awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

我们非常欢迎贡献者，也接受专利和商业软件.请先查看 [贡献指南](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md).

感谢所有的 [贡献者](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors), 没有你们的贡献，也不可能做的这么好。我们的目标是建立一个社区来驱动的资源知识库目录。

## 内容

* [常规](#常规)
* [框架, 程序集, 工具](#框架, 程序集, 工具)
  * [API](#api)
  * [应用框架](#应用框架)
  * [应用模板](#应用模板)
  * [身份验证和授权](#身份验证和授权)
  * [区块链](#区块链)
  * [机器人](#机器人)
  * [自动构建](#自动构建)
  * [Bundling and Minification](#bundling-and-minification)
  * [缓存](#缓存)
  * [内容管理系统](#内容管理系统)
  * [代码分析和性能检测](#代码分析和性能检测)  
  * [压缩](#压缩)
  * [编译, Transpilers and Languages](#compilers-transpilers-and-languages)
  * [密码学](#密码学)
  * [数据库](#数据库)
  * [数据库驱动](#数据库驱动)
  * [数据库工具和程序](#数据库工具和程序)
  * [日期和时间](#日期和时间)
  * [分布式计算](#分布式计算)
  * [电子商务和支付](#电子商务和支付)
  * [异常](#异常)
  * [函数式编程](#函数式编程)
  * [图形](#图形)
  * [GUI](#gui)
  * [IDE](#ide)
  * [国际化](#国际化)
  * [IOC框架](#IOC框架)
  * [日志](#日志)
  * [机器学习和数据科学](#机器学习和数据科学)
  * [邮件](#邮件)
  * [数值计算](#数值计算)
  * [网络](#网络)
  * [Misc](#misc)
  * [ORM](#orm)
  * [分析](#分析)
  * [消息队列](#消息队列)
  * [查询生成器](#查询生成器)
  * [任务调度](#任务调度)
  * [SDKs](#sdks)
  * [安全](#安全)
  * [搜索](#搜索)
  * [序列化](#序列化)
  * [测试](#测试)
  * [工具](#工具)
  * [Web框架](#Web框架)
  * [Web Socket](#web-socket)
  * [Windows服务](#Windows服务)
  * [工作流](#工作流)
* [初学者工具包](#初学者工具包)
* [示例项目](#示例项目)
* [文章](#articles)
* [书籍](#书籍)
* [视频](#视频)
* [播客](#播客)
* [社区](#社区)

## 常规

* [ASP.NET Core 文档](https://docs.asp.net/en/latest/) - 官方ASP.NET Core 文档网站.
* [.NET Core 文档](https://docs.microsoft.com/en-us/dotnet/articles/welcome) -.NET Core, C#, F# 和 Visual Basic的官方技术文档网站, 包括级别概念，入门指南和示例。
* [.NET Core SDK](https://www.microsoft.com/net/core) - .NET Core SDK是一个主要由微软和.NET社区在[GitHub](https://github.com/dotnet/core)维护的开发平台。
* [.NET 平台标准](https://github.com/dotnet/corefx/blob/master/Documentation/architecture/net-platform-standard.md) - 新的.NET平台版本与旧版本之间的差异。
* [.NET Standard 2.0介绍](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - The description of what will be going on for .NET Standard 2.0的将要发布的功能描述一级在当前.NET Standard 缺乏的一些功能组件的线路图。

## 框架, 程序集, 工具

### API
* [autorest](https://github.com/Azure/autorest) - 一个支持C#和Razor模板的Swagger(OpenAPI)规范的代码生成器，支持C#, Java, Node.js, TypeScript, Python 和 Ruby语言. `4.5.x or above`
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) - 一个使用Kestrel和Consul的反向API代理，包括了轻量级的consul的件。
* [Flurl](https://github.com/tmenier/Flurl) - 一个好用的.NET平台下URL构建器。 [http://tmenier.github.io/Flurl](http://tmenier.github.io/Flurl).
* GraphQL：GraphQL是一个由Facebook开发用于替换RESTful API的查询语言。
  * [graphql-convention](https://github.com/graphql-dotnet/conventions) - 该组件使用现有的属性和方法作为解析器，自动包装.NET类以满足GraphQL的架构定义。
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet) - ASP.NET Core平台的graphiql中间件。
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) -基于 [graphqljs](https://github.com/graphql/graphql-js)的.NET Core GraphQL组件。
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) -.NET GraphQL组件.
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) - Facebook GraphQL 查询语言 [GraphQL](https://fsprojects.github.io/FSharp.Data.GraphQL)的F#实现。.
  * [parser](https://github.com/graphql-dotnet/parser) - 一个.NET平台下GraphQL词法和语法分析器。
* [halcyon](https://github.com/visualeyes/halcyon) -一个ASP.NET 的HAL(Hypertext Application Language)实现。[HAL](http://www.cnblogs.com/daxnet/p/6327421.html),全称为Hypertext Application Language，它是一种简单的数据格式，它能以一种简单、统一的形式，在API中引入超链接特性，使得API的可发现性（discoverable）更强，并具有自描述的特点。
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core) - 一个目标是构建JSON API的框架,兼容api,目的是消除RESTful。
* [LightNode](https://github.com/neuecc/LightNode) - 基于[OWIN]( http://neuecc.github.io/LightNode)的微型RPC/REST框架。
* [NSwag](https://github.com/NSwag/NSwag) -针对.NET , Web API和TypeScript的Swagger API工具链 for .NET, Web API and 。The Swagger API toolchain for .NET, Web API and TypeScript [http://NSwag.org](http://NSwag.org).
* [OData](https://github.com/OData/WebApi/tree/feature/netcore) - 开放数据协议(OData)可以创建基于HTTP的数据服务，该服务允许使用统一资源标识符(uris)标识并在抽象数据模型中定义的资源，由Web客户机使用简单的HTTP发布和编辑消息。
* [refit](https://github.com/paulcbetts/refit) - 自动类型安全的REST库，支持Xamarin and .NET [http://paulcbetts.github.io/refit/](http://paulcbetts.github.io/refit/).
* [RESTClient .NET](https://bitbucket.org/MelbourneDeveloper/restclient-.net) - 一个支持所有.NET平台的简单REST客户端。
* [RestEase](https://github.com/canton7/RestEase) - 非常容易使用的，类型安全的REST API客户端 ,它简单并且可定制。
* [Swashbuckle](https://github.com/domaindrivendev/Ahoy) - 为web API添加swagger项目.
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) - ASP.NET Core的社区贡献.

### 应用框架
* [ABP](https://github.com/aspnetboilerplate/aspnetboilerplate) - 
ABP是一个通用的应用程序框架，特别为新的现代web应用程序设计。它使用已经熟悉的工具，并实现了最佳实践，从而为您提供了坚实的开发经验。
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET) - 一个高效可靠的UDP单播，UDP组播，IPC消息传输组件，是Aeron客户端的.NET版本.
* [akka.net](https://github.com/akkadotnet/akka.net) - 
一个在.Net和Mono平台上构建高并发、分布式和容错事件驱动应用程序的工具包和运行时。
* [ASP.NET MVC](https://github.com/aspnet/Mvc) - ASP.NET MVC框架。
* [CQRSlite](https://github.com/gautema/CQRSlite) - CQRS和Eventsourcing的轻量级辅助框架。
* [DotNetty](https://github.com/Azure/DotNetty) - netty的.NETk客户端,事件驱动的异步网络应用程序框架。
* [EmbedIO](https://github.com/unosquare/embedio) - 一个支持.NET和.NET Core的小型跨平台基于模块的Web服务器。
* [EventFlow](https://github.com/eventflow/EventFlow) - .NET平台的 Async/await CQRS+ES和DDD(邻域驱动设计)开发框架。
* [ExtCore](https://github.com/ExtCore) - 一个基于ASP.NET Core 1.0平台，免费开源和跨平台的创建模块化和可扩展Web应用程序框架。
* [Halibut](https://github.com/OctopusDeploy/Halibut) - 一个在SSL上使用json-rpc的安全通讯组件。
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp) - 远程过程调用(Remote Procedure call,rpc)为构建分布式应用程序和服务提供了一个抽象。这个库使用HTTP/2协议提供了gRPC协议的具体实现。这些库可以使用支持的语言组合，在客户端和服务器之间的通信。
* [MassTransit](https://github.com/MassTransit/MassTransit) - .NET的分布式应用程序框架. 
* [Nancy](https://github.com/NancyFx/Nancy) - 一个.NET和Mono平台，简单轻量级的构建基于HTTP的服务框架。
* [orleans](https://github.com/dotnet/orleans) - 可以构建大规模、高并发、分布式应用程序框架，而不需要学习专业分布式以及并发知识框架。
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet) - Ultra fast distributed actors for Golang and C# [http://proto.actor](http://proto.actor).
* [RService.io](https://github.com/Stoom/RService.IO) - ASP.Net Core RESTful microservice framework that focusing on speed and ease of use.
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all [https://servicestack.net](https://servicestack.net).
* [Steeltoe OSS](https://github.com/SteelToeOSS) - .NET常见的微服务模式工具包。

### 应用模板
* [ASP.NET Core Boilerplate](https://github.com/ASP-NET-Core-Boilerplate/Templates) - A professional ASP.NET MVC template for building secure, fast, robust and adaptable web applications or sites. It provides the minimum amount of code required on top of the default MVC template provided by Microsoft.
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template) - A ready-to-use templates for ASP.NET MVC 5 and ASP.NET Core with repositories, services, models mapping and DI and StyleCop warnings fixed.
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders) - Enable feature folders for MVC controllers and views in ASP.NET Core.
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio) - Template for Webpack, Visual Studio, ASP.NET Core and Angular. Both the client and the server side of the application are implemented inside one ASP.NET Core project which makes it easier to deploy.
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) - ASP.NET Core JavaScript服务.
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) - 一个基于jQuery的HTML5插件,用于构建现代化的web应用程序.. [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui).
* [QuickApp](https://github.com/emonney/QuickApp) - ASP.NET Core / Angular4 startup project template with complete login, user and role management.
* [Scaffolder](https://github.com/dncuug/scaffolder) - Lets you create extensible data-driven Web applications by automatically generated UI for each table in the database and  lets create a applications for viewing and editing data based on the schema of the data. 
* [Serenity](https://github.com/volkanceylan/Serenity) - Serenity is an ASP.NET MVC / TypeScript application platform designed to simplify and shorten development of data-centric business applications with a service based architecture.
* [Toucan](https://github.com/mrellipse/toucan) - Boilerplate for building single page apps. Server is multi-project .Net Core solution designed around SOLID principles. Client is TypeScript 2, Vuejs 2, Vuex 2.

### 身份验证和授权
* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) - OpenID Connect/OAuth2 server framework for OWIN/Katana and ASP.NET Core.
* [Auth0](https://github.com/auth0/auth0.net) - 一个企业级的身份验证和授权平台.
* [Identity](https://github.com/aspnet/Identity) - ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data.
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) - IdentityServer for ASP.NET Core 1.0 & 2.0
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) - EntityFramework persistence layer
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB) - MongoDB persistence layer
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - Entity Framework Core persistence layer
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates) - dotnet cli templates for IdentityServer4.
* [openiddict](https://github.com/openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - Build [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) with Stormpath and ASP.NET Core.
* [stuntman](https://github.com/ritterim/stuntman) - Library for impersonating users during development leveraging ASP.NET Identity.

### 区块链
* [NBitcoin](https://github.com/MetacoSA/NBitcoin) - 。NET框架最全面的比特币程序库。
* [Nethereum](https://github.com/Nethereum) - Bringing the love of Ethereum to .NET.

### Bot
* [NadekoBot](https://github.com/Kwoth/NadekoBot) - 一个C#编写的通用的开源聊天机器人.

### 自动构建
* [cake-build](https://github.com/cake-build/cake) - Cross platform build automation system. [http://cakebuild.net](http://cakebuild.net).
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your C# console output! [http://colorfulconsole.com](http://colorfulconsole.com).
* [dotnet-docker](https://github.com/dotnet/dotnet-docker) - The base Docker images for working with .NET Core and the .NET Core Tools.
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) - Go wrapper for the .NET Core Runtime.
* [msbuild](https://github.com/Microsoft/msbuild) - The Microsoft Build Engine is a platform for building applications.
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) - Visual Studio Team Services 构建和发布代理.

### Bundling and Minification
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) - 一个Visual Studio扩展,可以用于绑定配置和压缩js,css和html文件.
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine) - ASP.NET MVC ViewEngine for rendering markup in a JavaScript environment. Ideal for React and Angular server-side rendering.
* [Smidge](https://github.com/Shazwazza/Smidge/) - Lightweight runtime CSS/JavaScript file minification, combination, compression & management library for ASP.NET Core.
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin) - .NET library that contains a set of markup minifiers. The objective of this project is to improve the performance of web applications by reducing the size of HTML, XHTML and XML code.

### 缓存
* [CacheManager](https://github.com/MichaCo/CacheManager) - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [Foundatio](https://github.com/exceptionless/Foundatio) - Pluggable foundation blocks for building distributed apps.
* [Microsoft Caching](https://github.com/aspnet/Caching) - Libraries for in-memory caching and distributed caching.
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - High performance general purpose redis client for .NET languages (C# etc).

### 内容管理系统
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core) - 一个提供常规博客功能的ASP.NET应用程序.
* [Lynicon](https://github.com/jamesej/lyniconanc) - O/S ASP.Net Core/.Net Core CMS with paid for modules: JSON content, works with variety of data stores, c# content types
* [Orchard Core CMS](https://github.com/OrchardCMS/OrchardCore) - 开放源代码的内容管理系统,基于ASP.NET Core和一个模块化可扩展的应用框架. built with ASP.NET Core on top of a Modular and Extensible Application Framework.
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS) - 一个开源的ASP.NET Core 2.0 CMS. 支持MySQL,计划支持MSSQL, SQLite和PostgreSQL.同时它也是一个模块化的CMD,支持主题，皮肤，自定义布局,插件,多语言. Also it is a modular CMS supports theme, skin, custom layout, widgets, multiple language (En, BN).
* [Platformus](https://github.com/Platformus) - 免费开放源代码和跨平台的CMS.基于ASP.NET Core 1.0和ExeCor框架的.Free, open source and cross-platform CMS based on ASP.NET Core 1.0 and ExtCore framework.
* [SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent) -一个基于ASP.NET Core的简单灵活的内容和博客引擎. 
* [Squidex](https://github.com/Squidex/squidex) - 一个基于MongoDB/CQRS/EventSourcing的CMS系统.
* [Weapsy](https://github.com/Weapsy/Weapsy) - 基于DDD和CQRS的开源ASP.NET Core的CMS,支持MSSQL/MySQL/SQLite/PostgreSQL.

### 代码分析和性能检测
* [App.Metrics](https://github.com/alhardy/AppMetrics) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application and reports it's health. See the [docs](https://alhardy.github.io/app-metrics-docs/) for me details.
* [AspNet.Metrics](https://github.com/alhardy/aspnet-metrics) - Capturing CLR, application-level web request metrics. Middleware and extensions using [Metrics.Net](https://github.com/Recognos/Metrics.NET).
* [Audit.NET](https://github.com/thepirat000/Audit.NET) - 审计.NET对象变化的小框架.
* [BenchmarkDotNet](https://github.com/PerfDotNet/BenchmarkDotNet) - 强大的.NET测试组件.支持.NET Core,Mono和.NET Framework.
* [Foundatio](https://github.com/exceptionless/Foundatio#metrics) -一些常见的基础模块实现,包括程序集内存,Redis,StatSD和Metrics.NET.
* [MiniCover](https://github.com/lucaslorentz/minicover) - .NET Core下非常简洁的代码覆盖检测工具.
* [NBench](https://github.com/petabridge/NBench) - 。NET应用程序的性能基础测试和测试框架.
* [OpenCover](https://github.com/OpenCover/opencover) - 代码覆盖检查工具,仅支持.NET 2和以上(windows).
* [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials) - Visual Studio重构工具.

### 压缩
* [lz4net](https://github.com/MiloszKrajewski/lz4net) -.NET平台超快速的压缩算法.
* [sharpcompress](https://github.com/adamhathcock/sharpcompress) - 支持多种压缩类型和格式的纯C#托管类库.

### 编译, Transpilers and Languages
* [roslyn](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs. 
* [Sprache](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.

### 密码学
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) - BCrypt.NET的.NET Core版本,用于安全的存储密码.
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols.

### 数据库
* [DBreeze](https://github.com/hhblaze/DBreeze) - C# .NET MONO NOSQL (key value store embedded) ACID multi-paradigm database management system.
* [JsonFlatFileDataStore](https://github.com/ttu/json-flatfile-datastore) - Simple JSON flat file data store with support for typed and dynamic data.
* [LiteDB](https://github.com/mbdavid/LiteDB) - 一个.NET平台下的NoSQL文档数据库- [http://www.litedb.org](http://www.litedb.org).
* [NoDb](https://github.com/joeaudette/NoDb) -  .NET Core/ASP.NET平台下的"no database"文件存储系统, 因为不是每一个项目都需要一个数据库. because not every project needs a database.
* [marten](https://github.com/JasperFx/marten) - Postgresql as a Document Database and Event Store for .NET Applications [http://jasperfx.github.io/marten](http://jasperfx.github.io/marten).
* [yessql](https://github.com/sebastienros/yessql) - 和其他所有关系型数据库兼容的.NET文档数据库. document database working on any RDBMS.

### 数据库驱动
* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver) - DataStax C# Driver for Apache Cassandra.
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) - Confluent's Apache Kafka的 .NET客户端.
* [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net) - 一个.NET平台轻量级的可扩展的文档数据库引擎.A lightweight, document-oriented (NoSQL), syncable database engine for .NET.
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) - MongoDB的.NET驱动.
* MySQL
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0) - 一个mysql的纯托管ADO.NET驱动.Connector/Net is a fully-managed ADO.NET driver for MySQL.
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector) - Async MySQL Connector for .NET and .NET Core.
* Neo4j
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) - Neo4j Bolt的.NET驱动.
  * [Neo4jClient](https://github.com/Readify/Neo4jClient/tree/DotNetCore) - Neo4j的.NET客户端.
* [npgsql](https://github.com/npgsql/npgsql) - PostgreSQL的.NET驱动. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - Linq enabled document database for .NET.
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - C#/.NET RethinkDB driver with 100% ReQL API coverage.
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool) -Tarantool NoSql 数据库的.NET客户端.

### 数据库工具和程序
* [DbUp](https://github.com/DbUp/DbUp) - .NET library that helps you to deploy changes to SQL Server databases. It tracks which SQL scripts have been run already, and runs the change scripts that are needed to get your database up to date.
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData) - In-memory data cube with OLAP operations and PivotTable data model.

### 日期时间
* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) - 时间日期范围/间隔的扩展方法.
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime) - Allows you to write cleaner DateTime expressions and operation. Partially inspired by Ruby DateTime Extensions.
* [nodatime](https://github.com/nodatime/nodatime) - .NET下更好的日期时间操作API.Better date and time API for .NET [http://nodatime.org](http://nodatime.org).

### 分布式计算
* [Foundatio](https://github.com/exceptionless/Foundatio) - 可插入基础模块，构建分布式应用程序框架.

### 电子商务和支付
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - 基于.NET Core的超级简单的电子商务系统.
* [Stripe](https://github.com/ServiceStack/Stripe) - Typed .NET clients for stripe.com REST APIs.

### 异常
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - Exceptionless的.NET客户端

### 函数式编程
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - C#函数式编程的扩展.
* [FsCheck](https://github.com/fscheck/FsCheck) - .NET下的随机数测试.Random Testing for .NET
* [Giraffe](https://github.com/dustinmoris/Giraffe) - A native functional ASP.NET Core web framework for F# developers.
* [language-ext](https://github.com/louthy/language-ext) - C# functional language extensions and 'Erlang like' concurrency system.
* [LaYumba.Functional](https://github.com/la-yumba/functional-csharp-code) - Utility library for programming functionally in C#.
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions) - Effortlessly send messages anywhere on the network using Reactive Extensions (RX). Transport protocol is ZeroMQ.
* [Optional](https://github.com/nlkl/Optional) - A robust option type for C#.
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet) - [Reactive Streams](http://www.reactive-streams.org/) for .NET.
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - A MVVM framework that integrates with the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform.
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - The [Reactive Extensions](http://reactivex.io) for .NET.
* [Qactive](https://github.com/RxDave/Qactive) - Reactive queryable observable framework. `4.x.x or above`
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/c%23) - Functional Reactive Programming (FRP) Library. `4.x.x or above`

### 图形
* [GLFWDotNet](https://github.com/smack0007/GLFWDotNet) - .NET bindings for GLFW.
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) - A fluent wrapper around System.Drawing for the processing of image files [http://imageprocessor.org](http://imageprocessor.org). `4.5.x or above`
* [ImageSharp](https://github.com/JimBobSquarePants/ImageSharp) - 一个C#编写的处理图片文件的跨平台组件.[http://imageprocessor.org](http://imageprocessor.org).
* [QRCoder](https://github.com/codebude/QRCoder) - 一个纯C#编写的开源QR实现.A pure C# Open Source QR Code implementation.
* [SharpBgfx](https://github.com/MikePopoloski/SharpBgfx) - C# bindings for the bgfx graphics library.
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) - 支持.NET Core的图像处理组件
* [veldrid](https://github.com/mellinoe/veldrid) - A low-level, hardware-accelerated 3D graphics library for .NET.

### GUI
* [Avalonia](https://github.com/AvaloniaUI/Avalonia) - 一个支持多平台的.NET UI框架.(以前叫Perspex)A multi-platform .NET UI framework (formerly known as ).
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) - The Avalonia-based text editor component forked from [AvalonEdit](https://github.com/icsharpcode/AvalonEdit)
* [WinApi](https://github.com/prasannavl/WinApi) - A simple, direct, ultra-thin CLR library for high-performance Win32 Native Interop with automation, windowing, DirectX, OpenGL and Skia helpers.

### IDE
* [Mono](https://github.com/mono/monodevelop) - MonoDevelop enables developers to quickly write desktop and web applications on Linux, Windows and Mac OS X. It also makes it easy for developers to port .NET applications created with Visual Studio to Linux and Mac OS X maintaining a single code base for all platforms.
* [rider](https://www.jetbrains.com/rider/) - 基于IntelliJ平台和ReSharper的跨平台C# IDE.
* [Omnisharp](http://www.omnisharp.net/) - Family of Open Source projects, each with one goal: To enable a great .NET experience in YOUR editor of choice.
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) - SharpDevelop是一个微软.NET平台免费的集成开发环境(IDE),支持C#, VB.NET, Boo, IronPython, IronRuby 和 F# 项目.It is written (almost) entirely in C#, and comes with features you would expect in an IDE plus a few more.
* [Visual Studio Code](https://github.com/Microsoft/vscode) - New type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools.
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - 为个人开发者，开源项目,学术研究，教育，小型专业团队准备的免费编辑器.

### 国际化
* [Localization](https://github.com/aspnet/Localization) - Localization abstractions and implementations for ASP.NET Core applications.

### IOC框架
* [AutoDI](https://github.com/Keboo/AutoDI) - Super-fast compile-time dependency injection using IL weaving.
* [Autofac](https://github.com/autofac/Autofac) - Addictive .NET IoC container.
* [Castle.Windsor](https://github.com/castleproject/Windsor) Castle Windsor is a best of breed, mature Inversion of Control container available for .NET.
* [DryIoc](https://bitbucket.org/dadhi/dryioc) - Fast, small, full-featured IoC Container for .NET.
* [LightInject](https://github.com/seesharper/LightInject) - Ultra lightweight IoC container [http://www.lightinject.net](http://www.lightinject.net).
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - Easy, flexible, and fast Dependency Injection library that promotes best practice to steer developers towards the pit of success.
* [Stashbox](https://github.com/z4kn4fein/stashbox) - A lightweight, portable dependency injection framework for .NET based solutions.
* [StructureMap](https://github.com/structuremap/structuremap) - Dependency Injection/Inversion of Control tool for .NET.

### 日志
* [common-logging](https://github.com/net-commons/common-logging) - Portable logging abstraction for .NET [http://net-commons.github.io/common-logging](http://net-commons.github.io/common-logging).
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) - Logstash logging extension for .NET Core applications with UDP and Redis transports.
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - Exceptionless的.NET客户端.
* [Foundatio](https://github.com/exceptionless/Foundatio#logging) - A fluent logging api that can be used to log messages throughout your application.
* [LibLog](https://github.com/damianh/LibLog) - Single file for you to either copy/paste or install via nuget, into your library/ framework/ application to provide a logging abstraction.
* [log4net](https://github.com/apache/logging-log4net) - log4net is a port of the excellent Apache log4j™ framework to the Microsoft® .NET runtime.
* [NLog](https://github.com/NLog/NLog) - 一个高级的.NET, Silverlight和Xamarin平台的日志组件.
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) - Log appender for the build in ASP.NET Core logging to send all logs to Application Insights.
* [serilog](https://github.com/serilog/serilog) - 一个简单的.NET日志工具.

### 机器学习和数据科学
* [Accord](https://github.com/accord-net/framework) - .NET平台机器学习,计算机视觉,统计和数值计算科学的类库.
* [Spreads](https://github.com/Spreads/Spreads/) - Series and Panels for Real-time and Exploratory Analysis of Data Streams.

### 邮件
* [MailBody](https://github.com/doxakis/MailBody) - Create transactional email with a fluent interface (.NET).
* [MailKit](https://github.com/jstedfast/MailKit) - 一个跨平台的.NET 邮件类库，支持IMAP, POP3和SMTP.
* [MailMergeLib](https://github.com/axuno/MailMergeLib) - SMTP mail client library which provides comfortable mail merge capabilities for text, inline images and attachments, as well as good throughput and fault tolerance for sending mail messages.
* [MimeKit](https://github.com/jstedfast/MimeKit) - 跨平台 .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net/tree/dotnet-core) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint.
* [StrongGrid](https://github.com/Jericho/StrongGrid) - Client for SendGrid's v3 API. Not only allows you to send emails, but also allows you to bulk import contacts, manage lists and segments, create custom fields for your lists, etc. Also includes a parser for SendGrid Webhooks.

### 数值计算
* [UnitConversion](https://github.com/Stratajet/UnitConversion) - Expansible Unit Conversion Library for .NET Core and .NET Framework.

### Misc
* [AngleSharp](https://github.com/AngleSharp/AngleSharp) - The ultimate angle brackets parser library. It parses HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specification. Comparable to beautifulsoup4 of python.
* [aspnetcore-health](https://github.com/lurumad/aspnetcore-health) - Enables load balancers to monitor the status of deployed Web applications.
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) - Convention-based object-object mapper in .NET.
* [Castle.Core](https://github.com/castleproject/Core) - Castle Core, including Castle DynamicProxy, Logging Services and DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org).
* [Chessie](https://github.com/fsprojects/Chessie) - Railway-oriented programming for .NET [http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie).
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - The implementation of CommonMark specification in C# for converting Markdown documents to HTML.
* [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt) - Fluent library to create table for .NET console application.
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) - Microsoft ASP.NET server-side support and helpers for jQuery DataTables.
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) - Enums.NET is a high-performance type-safe .NET enum utility library
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/) - FTP and FTPS client, with extensive FTP commands, SSL/TLS connections, hashing/checksums and more.
* [HdrHistogram.NET](https://github.com/HdrHistogram/HdrHistogram.NET) - High Dynamic Range (HDR) Histogram.
* [httpclient-interception](https://github.com/justeat/httpclient-interception) - .NET Standard library for intercepting server-side HTTP dependencies.
* [Humanizer](https://github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities.
* [LibSass Host](https://github.com/Taritsyn/LibSassHost) - .NET wrapper around the [libSass](http://sass-lang.com/libsass) library with the ability to support a virtual file system.
* [markdig](https://github.com/lunet-io/markdig) - Fast, powerfull, CommonMark compliant, extensible Markdown processor for .NET.
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) - Parses string expressions (formulas, methods calls, conditions) to LINQ expression tree that can be compiled to lambda and evaluated.
* [Ocelot](https://github.com/TomPallister/Ocelot) - 使用.NET Core创建的APT网关.
* [readline](https://github.com/tsolarin/readline) - Pure C# GNU-Readline like library for .NET/.NET Core.
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASP.NET Core.
* [Relinq](https://github.com/re-motion/Relinq) - With re-linq, it's now easier than ever to create full-featured LINQ providers.
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net) - Html to Markdown converter library.
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) - PdfReport.Core is a code first reporting engine, which is built on top of the iTextSharp.LGPLv2.Core and EPPlus.Core libraries.
* [Polly](https://github.com/App-vNext/Polly) - .NET 3.5 / 4.0 / 4.5 / PCL library that allows developers to express transient exception and fault handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker in a fluent manner.
* [Scientist](https://github.com/github/Scientist.net) - .NET library for carefully refactoring critical paths. It's a port of GitHub's Ruby Scientist library.
* [Scrutor](https://github.com/khellang/Scrutor) - Assembly scanning extensions for Microsoft.Extensions.DependencyInjection.
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) - string.Format的一个扩展替换程序集.
* Stocks
  * [Trady](https://github.com/lppkarl/Trady) - Handy library for computing technical indicators, and it targets to be an automated trading system that provides stock data feeding, indicator computing, strategy building and automatic trading.
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core) - The .NET Standard (.NET Core) version from the System Linq Dynamic functionality.
* Validation
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) - Small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
  * [Valit](https://github.com/valit-stack/Valit) - A dead simple validation for .NET Core. No more if-statements all around your code. Write nice and clean fluent validators instead!
* [warden-stack](https://github.com/warden-stack) - "health checks" for your applications, resources and infrastructure. Keep your Warden on the watch.

### 网络
* [CurlThin](https://github.com/stil/CurlThin) - Lightweight cURL binding library for C# with support for multiple simultaneous transfers through curl_multi interface.
* [NETStandard.HttpListener](https://github.com/StefH/NETStandard.HttpListener) - HttpListener for .NET Core (NETStandard).

### ORM
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) - Familiar developer experience to previous versions of EF, including LINQ, POCO, and Code First support.
  * [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus) - Entity Framework Utilities | Bulk Operations | Batch Delete | Batch Update | Query Cache | Query Filter | Query Future | Query Include | Audit.
  * [LINQKit](https://github.com/scottksmith95/LINQKit) - A free set of extensions for LINQ to SQL and Entity Framework power users.
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) - Entity Framework Core provider for MySql built on top of mysql-net/MySqlConnector.
* [Dapper](https://github.com/StackExchange/Dapper) - Simple object mapper for .NET.
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper.
  * [Dommel](https://github.com/henkmollema/Dommel) - Simple CRUD operations for Dapper.
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) - CRUD for Dapper.
* [Limebean](https://nick-lucas.github.io/LimeBean/) - Hybrid-ORM, designed to be simple to use and not totally hide SQL, while having all the nice things you expect from an ORM. Inspired by RedBeanPHP.
* [LINQ to DB (linq2db)](https://linq2db.github.io/) - The fastest LINQ database access library offering a simple, lightweight, fast, and type-safe layer between your POCO objects and your database for more than 10 database engines with full SQL support.
* [NEventStore](https://github.com/NEventStore/NEventStore/tree/feature/dotnetcore) - Persistence library used to abstract different storage implementations when using event sourcing as storage mechanism. This library is developed with a specific focus on DDD/CQRS applications.
* [NPoco](https://github.com/schotime/NPoco) - Simple microORM that maps the results of a query onto a POCO object. Project based on Schotime's branch of PetaPoco.
* [NReco.Data](https://github.com/nreco/data) - Lightweight provider-independent DAL for SQL commands generation, CRUD operations and simple POCO mapping.
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - Light, simple and fast convention-based POCO ORM.
* [SqlFu](https://github.com/sapiens/SqlFu) - Fast and versatile Micro-ORM.
* [SQLStreamStore](https://github.com/SQLStreamStore/SQLStreamStore) - Stream Store library targeting SQL based implementations for .NET.

### 分析
* [Glimpse](http://getglimpse.com) - .NET平台下，开源轻量级的实时诊断分析器.
* [MiniProfiler](https://github.com/MiniProfiler/dotnet) - 一个简单高效的ASP.NET网站分析器.
* [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers) - Number of Roslyn diagnostic analyzers initially developed to help flesh out the design and implementation of the static analysis APIs.

### Query Builders
* [SqlKata](https://github.com/sqlkata/querybuilder) - 优雅的Sql查询生成器,支持复杂查询、连接、子查询,嵌套条件等等.

### 消息队列
* [emitter](https://emitter.io/) - 一个免费开源的实时详细服务，可以连接所有设备的，它的消息分发订阅API是基于速度和安全性设计的.
* [EventStore](https://github.com/EventStore/EventStore) - 开源的功能数据库,支持在JavaScript中的复杂事件处理. [https://geteventstore.com](https://geteventstore.com)
* [Foundatio](https://github.com/exceptionless/Foundatio#queues) - A common interface with in memory, redis and azure implementations.
* [MediatR](https://github.com/jbogard/MediatR) - 一个简单没有其他依赖的消息处理组件.
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) - MediatR extensions for Microsoft.Extensions.DependencyInjection.
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) -.Net平台简单直接的消息组件实现,支持发送命令,发布事件和请求响应.
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) - Simple in process mediator for .NET.
* [netmq](https://github.com/zeromq/netmq) -ZeroMQ在.NET平台的C#实现, 100% 原生C#代码.
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) - RabbitMQ .NET client [https://www.rabbitmq.com](https://www.rabbitmq.com).
* [RawRabbit](https://github.com/pardahlman/RawRabbit) - Modern .NET framework for communication over RabbitMq.
* [Rebus](https://github.com/rebus-org/Rebus) - Simple and lean service bus implementation for .NET.
* [Restbus](http://restbus.org) - RabbitMq的消息组件.
* [Tossit](https://github.com/turgayozgur/tossit) - Simple, easy to use library for distributed job/worker logic. Distributed messages handled by built in RabbitMQ implementation.

### 任务调度
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) - Lightweight robust library for running tasks(jobs) on schedules.
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface.
* [HangfireIO](https://github.com/HangfireIO/Hangfire) - Easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET apps [http://hangfire.io](http://hangfire.io).
* [LiquidState](https://github.com/prasannavl/LiquidState) - Efficient asynchronous and synchronous state machines for .NET
* [quartznet](https://github.com/quartznet/quartznet/) - Quartz企业级调度器. Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net).
* [stateless](https://github.com/dotnet-state-machine/stateless) - 使用C#代码创建状态机的简单组件.

### SDKs
* [AWS SDK](https://github.com/aws/aws-sdk-net) - The Amazon Web Services (AWS) .NET Core SDK components. Each AWS service has its own NuGet package.
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet) - Azure事件中心的.NET Standard 客户端.
* Blockchain clients
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net) - C# .Net wrapper for the Bittrex web API including all features easily accessible and usable.
  * [Binance.Net](https://github.com/JKorf/Binance.Net) - Binance网站web API的.NET包装.
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - Consul的.NET API.
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core) - A .NET Standard wrapper for the [Dark Sky API](https://darksky.net/dev/docs).
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) -Docker API的.NET(C#)客户端.
* [Microphone](https://github.com/rogeralsing/Microphone) - Lightweight framework to run self hosting REST services using Web Api or NancyFx ontop of a Consul or ETCD cluster.
* [NetTelegramBotApi](https://github.com/justdmitry/NetTelegramBotApi) - C# client library for building Telegram bot [https://core.telegram.org/bots/api](https://core.telegram.org/bots/api).
* [octokit.net](https://github.com/octokit/octokit.net) - GitHub的.NET API客户端组件..
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK) - The Open XML SDK provides tools for working with Office Word, Excel, and PowerPoint documents.
* [PreStorm](https://github.com/jshirota/PreStorm) - Parallel REST Client for ArcGIS Server.
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp) - C# client library for using the full SendGrid API.
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - .NET Standard compatible C# client to interface with Etsy's excellent [statsd](https://github.com/etsy/statsd) server.
* [tweetinvi](https://github.com/linvi/tweetinvi) - Intuitive .NET C# library to access the Twitter REST and STREAM API.

### 安全
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) - 纯净的HTML避免XSS攻击.
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - 处理JOSE对象的类库.() Library for processing JOSE objects (JWT, JWA, JWS and related).
* [NWebsec](https://github.com/NWebsec/NWebsec) - Security libraries for ASP.NET [https://www.nwebsec.com](https://www.nwebsec.com).
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard) - Roslyn analyzers that aim to help security audit on .NET applications.
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) - .NET Core middleware for injecting the Owasp recommended HTTP Headers for increased security.
* [Security](https://github.com/aspnet/Security) - Middleware for security and authorization of web apps.

### 搜索
* [AutoComplete](https://github.com/omerfarukz/autocomplete) - Persistent, simple, powerful and portable autocomplete library.
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) - Repository for both NEST and Elasticsearch.NET, the two official elasticsearch .NET clients.
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) - Elasticsearch .NET API.
* [SimMetrics.Net](https://github.com/StefH/SimMetrics.Net) - A Similarity Metric Library, e.g. from edit distance's (Levenshtein, Gotoh, Jaro etc) to other metrics, (e.g Soundex, Chapman)
* [SolrExpress](https://github.com/solr-express/solr-express) - 一个支持Solr的轻量级.NET查询组件.

### 序列化
* [bond](https://github.com/Microsoft/bond) - Cross-platform framework for working with schematized data. It supports cross-language de/serialization and powerful generic mechanisms for efficiently manipulating data. Bond is broadly used at Microsoft in high scale services.
* [Channels](https://github.com/davidfowl/Channels) - Push based .NET Streams.
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - 读写CSV文件的程序集. [http://csvhelper.com](http://csvhelper.com).
* [Edi.Net](https://github.com/indice-co/EDI.Net) - EDI 序列化/反序列化. 支持 EDIFact, X12 and TRADACOMS 格式.
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) - .NET平台,扩展的XML序列化的组件.
* [Jil](https://github.com/kevin-montrose/Jil) - 基于Sigil的.NET平台快速 JSON 序列化/反序列化的组件.
* [msgpack-cli](https://github.com/msgpack/msgpack-cli) - MessagePack的CLI实现.[msgpack.org](http://msgpack.org).
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - .NET平台广泛使用的高性能JSON框架.
* [protobuf-net](https://github.com/mgravell/protobuf-net/) - Protocol Buffers library for idiomatic .NET.
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET) - Schema.org objects turned into strongly typed C# POCO classes for use in .NET. All classes can be serialized into JSON/JSON-LD and XML, typically used to represent structured data in the head section of html page.
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) - JSON, JSV and CSV Text Serializers.
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) - Easy to use, easy to extend and high-performance library for CSV parsing with .NET.
* [Wire](https://github.com/rogeralsing/Wire) - Binary serializer for POCO objects.
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) - .NET
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter) - Fast binary (de)serializer for .NET.
* [YAXLib](https://github.com/sinairv/YAXLib) - XML Serialization Library for the .NET Framework and .NET Core. Extremely flexible and powerful.

### 测试
* [Bogus](https://github.com/bchavez/Bogus) - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [GenFu](https://github.com/MisterJames/GenFu) - Library you can use to generate realistic test data.
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) - The easy mocking library for .NET.
* [FluentAssertions](https://github.com/dennisdoomen/FluentAssertions) - Set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test.
* [moq.netcore](https://github.com/Moq/moq4) - Most popular and friendly mocking framework for .NET.
* [MSpec](https://github.com/machine/machine.specifications) - Popular testing framework for writing BDD-style tests.
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - Fluent testing
  framework for ASP.NET Core MVC.
* [Netling](https://github.com/hallatore/Netling) - Load tester client for easy web testing.
* [NSpec](https://github.com/nspec/NSpec) - Battle hardened testing framework for C# that's heavily inspired by Mocha and RSpec.
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) - A friendly substitute for .NET mocking frameworks.
* [nunit](https://github.com/nunit/dotnet-test-nunit) - NUnit test runner for .NET Core.
* [shouldly](https://github.com/shouldly/shouldly) - Should testing for .NET - the way Asserting *Should* be! [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore) - Pragmatic BDD solution for .NET. It uses the Gherkin specification language and integrates to Visual Studio.
* [Storyteller](https://github.com/storyteller/Storyteller) - Executable Specifications for .NET [http://storyteller.github.io](http://storyteller.github.io).
* [Stubbery](https://markvincze.github.io/Stubbery/) - A simple library for creating and running Api stubs in .NET.
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - The simplest BDD framework EVER!
* [xBehave.net](https://github.com/xbehave/xbehave.net) - An xUnit.net extension for describing your tests using natural language. [http://xbehave.github.io](http://xbehave.github.io)
* [xUnit.net](https://github.com/xunit/xunit) - A free, open source, community-focused unit testing tool for the .NET Framework. [https://xunit.github.io/](https://xunit.github.io/)

### 工具
* [CatLight](https://catlight.io) - Status notifier for developers that monitors builds and tasks in the project. Built using .Net Core and Electron.
* [CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils) - Command line parsing and utilities for .NET Core and .NET Framework.
* [docfx](https://github.com/dotnet/docfx) - Tools for building and publishing API documentation for .NET projects [http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [dotnetfiddle](https://dotnetfiddle.net) - .NET sandbox for developers to quickly try out code and share code snippets.
* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint) - Composable CLI (Command Line) Argument Parser for .Net Core & .Net Framework 4.5+.
* [Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server) - Fake REST API for prototyping or as a CRUD Back End. No need to define types, uses dynamic typing. Data is stored to a single JSON file. Has authentication, WebSocket notifications, async long running operations, random generation for errors/delays and experimental GraphQL support.
* [gitignore.io](https://github.com/joeblau/gitignore.io) - Create useful .gitignore files for your project [https://www.gitignore.io](https://www.gitignore.io).
* [GitInfo](https://github.com/kzu/GitInfo) - Git and SemVer Info from MSBuild, C# and VB.
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) - Scans uploaded packages.config files or GitHub repository and determines whether the nuget packages target .NET Standard [https://icanhasdot.net](https://icanhasdot.net).
* [json2csharp](http://json2csharp.com) - Generate C# classes from JSON.
* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple) - A Simple ACME Client for Windows.
* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) - Create, update and deploy Nuget Packages with a GUI.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through `projects.json` files efficiently with the OctoLinker browser extension for GitHub.
* [Opserver](https://github.com/opserver/Opserver) - Stack Exchange's Monitoring System.
* [ShareX](https://github.com/ShareX/ShareX) - Free and open source program that lets you capture or record any area of your screen and share it with a single press of a key. It also allows uploading images, text or other types of files to over 80 supported destinations you can choose from. [https://getsharex.com](https://getsharex.com)
* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap) – Simple sitemap generator for .NET and .NET Core
* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS) – Simple RSS Feed generator for .NET and .NET Core

### Web框架
* [Blazor](https://github.com/SteveSanderson/Blazor) - 在浏览器中通过WebAssembly运行.NET的 UI 框架.
* [ReactJS.NET](https://github.com/reactjs/React.NET) - .NET library for JSX compilation and server-side rendering of React components.
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET) - Predictable state container for .NET apps. Inspired by [https://github.com/reactjs/redux](https://github.com/reactjs/redux).

### Web Socket
* [SignalR Server](https://github.com/aspnet/signalr) - Real-time web functionality for web apps, including server-side push.
* [SuperSocket](https://github.com/kerryjiang/SuperSocket) - Light weight, cross platform and extensible socket server application framework.
* [WampSharp](https://github.com/Code-Sharp/WampSharp) - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) - Protocol that provides messaging patterns of Remote Procedure Calls and Publish/Subscribe over WebSockets.
* [websocket-manager](https://github.com/radu-matei/websocket-manager) - Real-Time library for ASP .NET Core.

### Windows服务
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) - 从 .NET Core中直接安装和运行windows服务.
* [Topshelf](https://github.com/Topshelf/Topshelf) - Easy service hosting framework for building Windows services using .NET. `4.5.x or above`

### 工作流
* [CoreWF](https://github.com/dmetzgar/corewf/) - Port of Windows Workflow Foundation (WF) to .NET Core.
* [workflow-core](https://github.com/danielgerlag/workflow-core) - .NET Standard平台的轻量级工作流引擎.

## 初学者工具包
* [Arch](https://github.com/Arch) - The collection of .NET Core libraries that are created by software architects who embrace all the new stuff in .NET Core.
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal) - Cross-platform - w/ server-side rendering for SEO, Bootstrap, i18n internationalization (ngx-translate), Webpack, TypeScript, unit testing w/ Karma, WebAPI REST setup, SignalR, Swagger docs, and more!
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate is a starting point for new modern web applications using best practices and most popular tools. It's aimed to be a SOLID model, a general-purpose application framework and a project template. `4.5.x or above`
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) - Yeoman generator to build a brand-new ASP.NET Core single page application that uses Angular 2 / React / React With Redux / Knockout / Aurelia on the client.
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter) - Asp.NETCore 2.0 Vue 2 (ES6) SPA Starter kit, contains routing, Vuex, and more!.
* [bitwarden-core](https://github.com/bitwarden/core) - The core infrastructure backend (API, database, etc) [https://bitwarden.com](https://bitwarden.com).
* [dotNetify](https://github.com/dsuryd/dotNetify) - Simple, lightweight, yet powerful way to build real-time HTML5/C# .NET web apps.
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet) - yo generator for ASP.NET Core.
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - Starting point for building isomorphic React applications with ASP.NET Core 1, leveraging existing techniques.
* [saaskit](https://github.com/saaskit/saaskit) - Developer toolkit for building SaaS applications.

## 示例项目
* [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) - West Wind Album Viewer ASP.NET 5 Sample.
* [allReady](https://github.com/HTBox/allReady) - Open-source solution focused on increasing awareness, efficiency and impact of preparedness campaigns as they are delivered by humanitarian and disaster response organizations in local communities. [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
* [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) - ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
* [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) - Samples of implementing Service Discovery patterns with ASP.NET Core.
* [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop) - A workshop for moving through the various new pieces in ASP.NET Core Authorization
* [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) Presented December Connect 2016 Conference, a compreshsive set of interworking apps for both enterprise users and the consumers (bike riders):
 [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps), [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices), [Websites](https://github.com/Microsoft/BikeSharing360_Websites), [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer), [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer), [Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp),
 [Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps).
* [cloudscribe](https://github.com/joeaudette/cloudscribe) - ASP.NET Core Multi-tenant web application foundation.
* [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp) - An Open Source Website for running small, local development events.
* [distributed-playground](https://github.com/jvandevelde/distributed-playground) - Distributed service playground with Vagrant, Consul, Docker & ASP.NET Core.
* [DotNetClub](https://github.com/scheshan/DotNetClub) - Tiny club written in ASP.NET Core.
* [Entropy](https://github.com/aspnet/Entropy) - Chaotic experimental playground for new features and ideas - check here for small and simple samples for individual features.
* [EquinoxProject](https://github.com/EduardoPires/EquinoxProject) - Full ASP.NET Core 2.0 application with DDD, CQRS and Event Sourcing.
* [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) - Microservices Architecture and Containers based Reference Application.
* [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) - How to manage user identities in a multitenant app on Microsoft Azure, using Azure Active Directory for authentication.
* [magazine-website](https://github.com/thangchung/magazine-website) - Magazine website (using .NET Core, ASP.NET Core, EF Core) with DDD, CQRS, microservices, asynchronous programming applied.
* [MegaMine](https://github.com/Nootus/MegaMine) - Open source mining solution that helps miners in extracting Gold, Quartz, Granite etc. This solution is built using ASP.NET Core and AngularJS utilizing multiple light weight components in a Microservices way.
* [minicompiler](https://github.com/ealsur/minicompiler) - Minification, bundling and compiling sample.
* [MusicStore](https://github.com/aspnet/MusicStore) - Sample MusicStore application that uses MVC and Entity Framework.
* [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) - NLayerAppV3 N-Layered Architecture with .NET Core Preview 2.
* [Orchard Core - Modular and Multi-tenant applications](https://github.com/OrchardCMS/OrchardCore.Samples) - Use Orchard Core Framework to create Modular and Multi-tenant applications.
* [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Real-time trading platform demo showcasing reactive programming principles applied across the full application stack.
* [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) - Cross-platform Single Page Applications with ASP.NET Core, Angular 2 & TypeScript [http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L).
* [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) - A daily updated micro samples of ASP.NET Core features and facilities.
* [JustA.ML](https://github.com/mustakimali/JustA.ML) - A web application that lets you share files/URL/text between your devices written in ASP.NET Core 2.0. Open source, live at [https://justa.ml](https://justa.ml)

## 文章
* Basic knowledge
  * [A guide to the .NET Core projects on GitHub](https://blog.rendle.io/a-guide-to-the-net-projects-on-github/)
  * [Microsoft architectual overview of comprehensive BikeSharing360 suite of demo apps with related videos](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [Porting a .NET Framework library to .NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [The 68 things the CLR does before executing a single line of your code](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * The comparison between .NET Core and Nodejs at [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) and [here](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
  * [Understanding ASP.NET Core Initialization](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
  * [Why you should join .NET Core and ASP.NET Core train](https://codingblast.com/why-you-should-join-asp-net-core/)
* Cloud Development
  * [Configuring the AWS SDK in .NET Core](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [Serverless Architecture using C# and AWS Amazon Gateway Api/Lambda](https://www.codeproject.com/Articles/1178781/Serverless-Architecture-using-Csharp-and-AWS-Amazo)
  * [Using C# and .NET Core in Amazon Web Services (AWS) Lambda](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
* Configuration and deployment
  * [.NET project structure](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)
  * [Adding Travis CI builds to a .NET Core app](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0 - Configure ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy, nginx, Angular 2, ASP.NET Core, Redis and Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Project.json to MSBuild conversion guide](http://www.natemcmaster.com/blog/2017/01/19/project-json-to-csproj/)
  * [Publishing a .NET project with Appveyor and NuGet](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
* Entity Framework Core
  * [.NET Core Data Access](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [A very good example about EF Core](https://github.com/rowanmiller/Demo-EFCore)
* Miraculous
  * [Getting started with Orchard Core as a NuGet package](http://www.ideliverable.com/blog/getting-started-with-orchard-core-as-a-nuget-package)
  * [How to export HTML to PDF in ASP.NET Core](https://code.msdn.microsoft.com/How-to-export-HTML-to-PDF-c5afd0ce)
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* Security
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [ASP.NET Core 2.0 Authentication and Authorization System Demystified](https://digitalmccullough.com/posts/aspnetcore-auth-system-demystified.html)
  * [A walk-through for an ASP.NET Authorization Lab](https://github.com/blowdart/AspNetAuthorizationWorkshop)
  * [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
* Testing
  * [Selenium with .NET Core](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)

## 书籍
* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-dot-net-core-in-action)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [Dependency Injection in .NET Core, 2nd edition](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [Exploring .NET Core with Microservices, ASP.NET Core, and Entity Framework Core - free eBook sampler](https://www.manning.com/books/exploring-dot-net-core)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [The little ASP.NET Core](https://www.recaffeinate.co/book)

## 视频
* [Channel9](https://channel9.msdn.com)
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)
* [.NET World](https://www.youtube.com/channel/UClW5uIyHKPhfSEloQxn7b0Q)

## 播客
* [.NET Rocks](https://www.dotnetrocks.com)
* [Static Void Podcast](https://www.staticvoidpodcast.com)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## 社区
* [ASP.NET](https://forums.asp.net)
* [.NET Foundation](http://forums.dotnetfoundation.org)
* [Channel9](https://channel9.msdn.com/Forums)
* [Slack](http://tattoocoder.com/aspnet-slack-sign-up)
* Stack Overflow
  *  [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
  *  [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  *  [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
  *  [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  *  [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  *  [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [thangchung](http://weblogs.asp.net/thangchung) has waived all copyright and related or neighboring rights to this work.
