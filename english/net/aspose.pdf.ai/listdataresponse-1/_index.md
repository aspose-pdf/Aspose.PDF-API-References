---
title: "ListDataResponse<T> Class"
linktitle: "ListDataResponse<T>"
articleTitle: "ListDataResponse<T>"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.ListDataResponse class. Represents a list data response containing additional information such as first and last IDs and whether there are more..."
type: docs
weight: 720
url: "/net/aspose.pdf.ai/listdataresponse-1/"
keywords: "ListDataResponse<T>, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ListDataResponse&lt;T&gt; class

Represents a list data response containing additional information such as first and last IDs and whether there are more items.

```csharp
public class ListDataResponse<T> : DataResponse<T>
```

## Type Parameters

| Name | Description |
| --- | --- |
| T |  |

## Constructors

| Name | Description |
| --- | --- |
| [ListDataResponse](./listdataresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Data](../../aspose.pdf.ai/dataresponse-1/data/) { get; set; } | Gets or sets the data in the response. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [FirstId](./firstid/) { get; set; } | Gets or sets the first ID in the list. |
| [HasMore](./hasmore/) { get; set; } | Gets or sets a value indicating whether there are more items in the list. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [LastId](./lastid/) { get; set; } | Gets or sets the last ID in the list. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |

### See Also

* class [DataResponse<T>](../dataresponse-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

