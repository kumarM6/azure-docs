---
title: 'Azure Cosmos DB: SQL .NET API, SDK & resources'
description: Learn all about the SQL .NET API and SDK including release dates, retirement dates, and changes made between each version of the Azure Cosmos DB .NET SDK.
author: rothja
ms.service: cosmos-db
ms.subservice: cosmosdb-sql
ms.devlang: csharp
ms.topic: reference
ms.date: 04/18/2022
ms.author: jroth
ms.custom: devx-track-dotnet

---
# Azure Cosmos DB .NET SDK v2 for SQL API: Download and release notes (Legacy)
[!INCLUDE[appliesto-sql-api](../includes/appliesto-sql-api.md)]

[!INCLUDE[appliesto-sql-api](../includes/cosmos-db-sdk-list.md)]

| | Links |
|---|---|
|**Release notes**|[Release notes](https://github.com/Azure/azure-cosmos-dotnet-v2/blob/master/changelog.md)|
|**SDK download**|[NuGet](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB/)|
|**API documentation**|[.NET API reference documentation](/dotnet/api/overview/azure/cosmosdb)|
|**Samples**|[.NET code samples](https://github.com/Azure/azure-cosmos-dotnet-v2/tree/master/samples)|
|**Get started**|[Get started with the Azure Cosmos DB .NET SDK](sql-api-get-started.md)|
|**Web app tutorial**|[Web application development with Azure Cosmos DB](sql-api-dotnet-application.md)|
|**Current supported framework**|[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?id=30653)|

> [!WARNING]
> On August 31, 2024 the Azure Cosmos DB .NET SDK v2.x will be retired; the SDK and all applications using the SDK will continue to function;
> Azure Cosmos DB will simply cease to provide further maintenance and support for this SDK. 
> We recommend [migrating to the latest version](migrate-dotnet-v3.md) of the .NET SDK v3 SDK.
>

> [!NOTE]
> If you are using .NET Framework, please see the latest version 3.x of the [.NET SDK](sql-api-sdk-dotnet-standard.md), which targets .NET Standard.

## <a name="release-history"></a> Release history

Release history is maintained in the Azure Cosmos DB .NET SDK source repo. For a detailed list of feature releases and bugs fixed in each release, see the [SDK changelog documentation](https://github.com/Azure/azure-cosmos-dotnet-v2/blob/master/changelog.md)

Because version 3 of the Azure Cosmos DB .NET SDK includes updated features and improved performance, The 2.x of this SDK will be retired on 31 August 2024. You must update your SDK to version 3 by that date. We recommend following the [instructions](migrate-dotnet-v3.md) to migrate to Azure Cosmos DB .NET SDK version 3.

## <a name="recommended-version"></a> Recommended version

Different sub versions of .NET SDKs are available under the 2.x.x version. **The minimum recommended version is 2.18.0**.

## <a name="known-issues"></a> Known issues

Below is a list of any known issues affecting the [recommended minimum version](#recommended-version):

| Issue | Impact | Mitigation | Tracking link |
| --- | --- | --- | --- |

## FAQ

[!INCLUDE [cosmos-db-sdk-faq](../includes/cosmos-db-sdk-faq.md)]

## See also

To learn more about Cosmos DB, see [Microsoft Azure Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) service page.
