---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepResponse class. Represents a step in execution of a run
type: docs
weight: 1140
url: /net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

Represents a step in execution of a run.

```csharp
public class RunStepResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Gets or sets the ID of the assistant associated with the run step. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step was cancelled. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step completed. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step expired. A step is considered expired if the parent run is expired. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run step failed. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Gets or sets the identifier of the run step, which can be referenced in API endpoints. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Gets or sets the last error associated with this run step. Will be null if there are no errors. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Gets or sets the object type, which is always thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Gets or sets the ID of the run that this run step is a part of. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Gets or sets the type of run step, which can be either message_creation or tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Gets or sets the status of the run step, which can be either in_progress, cancelled, failed, completed, or expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Gets or sets the details of the run step. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Gets or sets the ID of the thread that was run. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Gets or sets usage statistics related to the run step. This value will be null while the run step's status is in_progress. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


