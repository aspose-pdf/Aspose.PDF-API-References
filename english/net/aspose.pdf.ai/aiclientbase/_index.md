---
title: "AIClientBase Class"
linktitle: "AIClientBase"
articleTitle: "AIClientBase"
second_title: "Aspose.PDF for .NET"
description: "Represents client to access AI API."
type: docs
weight: 20
url: "/net/aspose.pdf.ai/aiclientbase/"
keywords: "AIClientBase, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## AIClientBase class

Represents client to access AI API.

```csharp
public abstract class AIClientBase : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [AIClientBase](./aiclientbase/#constructor)(*HttpClient*) | Initializes a new instance of the [`AIClientBase`](../../aspose.pdf.ai/aiclientbase/) class. |

## Properties

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](./backoffdelayseconds/) { get; set; } | Gets or sets the backoff delay in seconds. |
| [HttpRequestMaxRetries](./httprequestmaxretries/) { get; set; } | Gets or sets the maximum number of HTTP request retries. |
| [PollingIntervalSeconds](./pollingintervalseconds/) { get; set; } | Gets or sets the polling interval in seconds. |
| [PollingTimeoutSeconds](./pollingtimeoutseconds/) { get; set; } | Gets or sets the polling timeout in seconds. |

## Methods

| Name | Description |
| --- | --- |
| [AssertDisposed](./assertdisposed/) | Asserts whether the object has been disposed. |
| [Dispose](./dispose/) | Disposes of the resources used by the [`AIClientBase`](../../aspose.pdf.ai/aiclientbase/). |
| [Dispose](./dispose/)(*bool*) | Disposes of the resources used by the [`AIClientBase`](../../aspose.pdf.ai/aiclientbase/). |
| [HandleRequestAsync](./handlerequestasync/)(*Func<Task<T0>>, Func<string, string>, Nullable<CancellationToken>*) |  |
| [PollForCompletionAsync](./pollforcompletionasync/)(*Func<Task<IStatus>>, Nullable<CancellationToken>*) | Polls for completion asynchronously with a specified request delegate. |
| [PollForCompletionAsync](./pollforcompletionasync/)(*Func<Task<T0>>, Func<T0, bool>, Nullable<CancellationToken>*) |  |

## Fields

| Name | Description |
| --- | --- |
| [Disposed](./disposed/) |  |
| [HttpClient](./httpclient/) |  |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

