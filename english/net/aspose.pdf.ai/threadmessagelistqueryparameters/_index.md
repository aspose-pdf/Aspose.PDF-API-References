---
title: "ThreadMessageListQueryParameters Class"
linktitle: "ThreadMessageListQueryParameters"
articleTitle: "ThreadMessageListQueryParameters"
second_title: "Aspose.PDF for .NET"
description: "Query parameters object for listing thread messages."
type: docs
weight: 1220
url: "/net/aspose.pdf.ai/threadmessagelistqueryparameters/"
keywords: "ThreadMessageListQueryParameters, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ThreadMessageListQueryParameters class

Query parameters object for listing thread messages.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageListQueryParameters](./threadmessagelistqueryparameters/#constructor) | Initializes a new instance of the ThreadMessageListQueryParameters class. |

## Properties

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Gets or sets a cursor for use in pagination. after is an object ID that defines your place in the list. *(Inherited from BaseListQueryParameters)* |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Gets or sets a cursor for use in pagination. before is an object ID that defines your place in the list. *(Inherited from BaseListQueryParameters)* |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Gets or sets a limit on the number of objects to be returned. Limit can range between 1 and 100, and. *(Inherited from BaseListQueryParameters)* |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Gets or sets sort order by the created_at timestamp of the objects. asc for ascending order. *(Inherited from BaseListQueryParameters)* |
| [RunId](./runid/) { get; set; } | Filter messages by the run ID that generated them. |

## Methods

| Name | Description |
| --- | --- |
| [GetQueryParameters](./getqueryparameters/) | Gets the query parameters for listing thread messages. |

### See Also

* class [BaseListQueryParameters](../baselistqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

