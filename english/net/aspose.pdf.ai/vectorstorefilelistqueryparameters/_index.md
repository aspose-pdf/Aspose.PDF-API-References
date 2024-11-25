---
title: Class VectorStoreFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileListQueryParameters class. Query parameters object for listing vector store files
type: docs
weight: 1330
url: /net/aspose.pdf.ai/vectorstorefilelistqueryparameters/
---
## VectorStoreFileListQueryParameters class

Query parameters object for listing vector store files.

```csharp
public class VectorStoreFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreFileListQueryParameters](vectorstorefilelistqueryparameters/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Gets or sets a cursor for use in pagination. after is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with obj_foo, your subsequent call can include after=obj_foo in order to fetch the next page of the list. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Gets or sets a cursor for use in pagination. before is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with obj_foo, your subsequent call can include before=obj_foo in order to fetch the previous page of the list. |
| [Filter](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/filter/) { get; set; } | Gets or sets a filter by file status. One of in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Gets or sets a limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Gets or sets sort order by the created_at timestamp of the objects. asc for ascending order and desc for descending order. |

## Methods

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/getqueryparameters/)() | Gets the query parameters for listing vector store files. |

### See Also

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


