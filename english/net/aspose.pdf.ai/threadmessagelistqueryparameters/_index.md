---
title: Class ThreadMessageListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageListQueryParameters class. Query parameters object for listing thread messages
type: docs
weight: 1130
url: /net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## ThreadMessageListQueryParameters class

Query parameters object for listing thread messages.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Gets or sets a cursor for use in pagination. after is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with obj_foo, your subsequent call can include after=obj_foo in order to fetch the next page of the list. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Gets or sets a cursor for use in pagination. before is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with obj_foo, your subsequent call can include before=obj_foo in order to fetch the previous page of the list. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Gets or sets a limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Gets or sets sort order by the created_at timestamp of the objects. asc for ascending order and desc for descending order. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Filter messages by the run ID that generated them. |

## Methods

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Gets the query parameters for listing thread messages. |

### See Also

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


