---
title: "AIClientBase.PollForCompletionAsync"
linktitle: "PollForCompletionAsync"
articleTitle: "PollForCompletionAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "AIClientBase method. Polls for completion asynchronously with a specified request delegate."
type: docs
weight: 50
url: "/net/aspose.pdf.ai/aiclientbase/pollforcompletionasync/"
product_version: "26.9.0"
---
## PollForCompletionAsync(Func<Task<IStatus>>, Nullable<CancellationToken>) {#pollforcompletionasync}

Polls for completion asynchronously with a specified request delegate.

```csharp
protected Task<IStatus> PollForCompletionAsync(Func<Task<IStatus>> requestDelegate, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| requestDelegate | Func<Task<IStatus>> | The asynchronous request delegate. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[IStatus](../../../aspose.pdf.ai/istatus/)>

The status of the completion.

### See Also

* class [AIClientBase](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## PollForCompletionAsync(Func<Task<T0>>, Func<T0, bool>, Nullable<CancellationToken>) {#pollforcompletionasync_1}

Polls for completion asynchronously with a specified request delegate and completion check.

```csharp
protected Task<T0> PollForCompletionAsync(Func<Task<T0>> requestDelegate, Func<T0, bool> isComplete, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| requestDelegate | Func<Task<T0>> | The asynchronous request delegate. |
| isComplete | Func<T0, bool> | The completion check function. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<T0>

The result of the completion.

### See Also

* class [AIClientBase](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

