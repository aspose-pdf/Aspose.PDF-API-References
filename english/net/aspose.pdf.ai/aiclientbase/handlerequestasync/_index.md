---
title: "AIClientBase.HandleRequestAsync"
linktitle: "HandleRequestAsync"
articleTitle: "HandleRequestAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "AIClientBase method. Handles the asynchronous request with retries and backoff delay."
type: docs
weight: 40
url: "/net/aspose.pdf.ai/aiclientbase/handlerequestasync/"
product_version: "26.9.0"
---
## HandleRequestAsync(Func<Task<T0>>, Func<string, string>, Nullable<CancellationToken>) {#handlerequestasync}

Handles the asynchronous request with retries and backoff delay.

```csharp
protected Task<T0> HandleRequestAsync(Func<Task<T0>> requestDelegate, Func<string, string> exceptionMessageDelegate, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| requestDelegate | Func<Task<T0>> | The asynchronous request delegate. |
| exceptionMessageDelegate | Func<string, string> | The delegate to generate exception messages. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<T0>

The response of type .

### See Also

* class [AIClientBase](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

