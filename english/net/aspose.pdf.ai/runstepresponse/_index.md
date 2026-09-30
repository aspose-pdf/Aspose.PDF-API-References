---
title: "RunStepResponse Class"
linktitle: "RunStepResponse"
articleTitle: "RunStepResponse"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.RunStepResponse class. Represents a step in execution of a run."
type: docs
weight: 1140
url: "/net/aspose.pdf.ai/runstepresponse/"
keywords: "RunStepResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## RunStepResponse class

Represents a step in execution of a run.

```csharp
public class RunStepResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [RunStepResponse](./runstepresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](./assistantid/) { get; set; } | Gets or sets the ID of the assistant associated with the run step. |
| [CancelledAt](./cancelledat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step was cancelled. |
| [CompletedAt](./completedat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step completed. |
| [CreatedAt](./createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [ExpiredAt](./expiredat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step expired. A step is considered expired if the parent run is expired. |
| [FailedAt](./failedat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step failed. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](./id/) { get; set; } | Gets or sets the identifier of the run step, which can be referenced in API endpoints. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [LastError](./lasterror/) { get; set; } | Gets or sets the last error associated with this run step. Will be null if there are no errors. |
| [Metadata](./metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [RunId](./runid/) { get; set; } | Gets or sets the ID of the run that this run step is a part of. |
| [RunStepType](./runsteptype/) { get; set; } | Gets or sets the type of run step, which can be either message_creation or tool_calls. |
| [Status](./status/) { get; set; } | Gets or sets the status of the run step, which can be either in_progress, cancelled, failed, completed, or expired. |
| [StepDetails](./stepdetails/) { get; set; } | Gets or sets the details of the run step. |
| [ThreadId](./threadid/) { get; set; } | Gets or sets the ID of the thread that was run. |
| [Usage](./usage/) { get; set; } | Gets or sets usage statistics related to the run step. This value will be null while the run step's status is in_progress. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

