---
title: "VectorStoreFileListQueryParameters Class"
linktitle: "VectorStoreFileListQueryParameters"
articleTitle: "VectorStoreFileListQueryParameters"
second_title: "Aspose.PDF for .NET"
description: "Query parameters object for listing vector store files."
type: docs
weight: 1420
url: "/net/aspose.pdf.ai/vectorstorefilelistqueryparameters/"
keywords: "VectorStoreFileListQueryParameters, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## VectorStoreFileListQueryParameters class

Query parameters object for listing vector store files.

```csharp
public class VectorStoreFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreFileListQueryParameters](./vectorstorefilelistqueryparameters/#constructor) | Initializes a new instance of the VectorStoreFileListQueryParameters class. |

## Properties

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Gets or sets a cursor for use in pagination. after is an object ID that defines your place in the list. *(Inherited from BaseListQueryParameters)* |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Gets or sets a cursor for use in pagination. before is an object ID that defines your place in the list. *(Inherited from BaseListQueryParameters)* |
| [Filter](./filter/) { get; set; } | Gets or sets a filter by file status. One of in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Gets or sets a limit on the number of objects to be returned. Limit can range between 1 and 100, and. *(Inherited from BaseListQueryParameters)* |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Gets or sets sort order by the created_at timestamp of the objects. asc for ascending order. *(Inherited from BaseListQueryParameters)* |

## Methods

| Name | Description |
| --- | --- |
| [GetQueryParameters](./getqueryparameters/) | Gets the query parameters for listing vector store files. |

### See Also

* class [BaseListQueryParameters](../baselistqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

