---
title: "RunResponse Class"
linktitle: "RunResponse"
articleTitle: "RunResponse"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.RunResponse class. Represents an execution run on a thread."
type: docs
weight: 1100
url: "/net/aspose.pdf.ai/runresponse/"
keywords: "RunResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## RunResponse class

Represents an execution run on a thread.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [RunResponse](./runresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](./assistantid/) { get; set; } | Gets or sets the ID of the assistant used for execution of this run. |
| [CancelledAt](./cancelledat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run was cancelled. |
| [CompletedAt](./completedat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run was completed. |
| [CreatedAt](./createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [ExpiresAt](./expiresat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run will expire. |
| [FailedAt](./failedat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run failed. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](./id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. |
| [IncompleteDetails](./incompletedetails/) { get; set; } | Gets or sets the details on why the run is incomplete. Will be null if the run is not incomplete. |
| [Instructions](./instructions/) { get; set; } | Gets or sets the instructions that the assistant used for this run. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [LastError](./lasterror/) { get; set; } | Gets or sets the last error associated with this run. Will be null if there are no errors. |
| [MaxCompletionTokens](./maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens specified to have been used over the course of the run. |
| [MaxPromptTokens](./maxprompttokens/) { get; set; } | Gets or sets the maximum number of prompt tokens specified to have been used over the course of the run. |
| [Metadata](./metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Model](./model/) { get; set; } | Gets or sets the model that the assistant used for this run. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [RequiredAction](./requiredaction/) { get; set; } | Gets or sets the details on the action required to continue the run. Will be null if no action is required. |
| [ResponseFormat](./responseformat/) { get; set; } | Gets or sets the format that the model must output. Compatible with GPT-4o, GPT-4 Turbo, and all GPT-3.5 Turbo models since gpt-3.5-turbo-1106. Setting to { "type": "json_object" } enables JSON mode, which guarantees the message the model generates is valid JSON. Important: when using JSON mode, you must also instruct the model to produce JSON yourself via a system or user message. Without this, the model may generate an unending stream of whitespace until the generation reaches the token limit, resulting in a long-running and seemingly "stuck" request. Also note that the message content may be partially cut off if finish_reason="length", which indicates the generation exceeded max_tokens or the conversation exceeded the max context length. |
| [StartedAt](./startedat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the run was started. |
| [Status](./status/) { get; set; } | Gets or sets the status of the run, which can be either queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete, or expired. |
| [Temperature](./temperature/) { get; set; } | Gets or sets the sampling temperature used for this run. If not set, defaults to 1. |
| [ThreadId](./threadid/) { get; set; } | Gets or sets the ID of the thread that was executed on as a part of this run. |
| [ToolChoice](./toolchoice/) { get; set; } | Gets or sets which (if any) tool is called by the model. none means the model will not call any tools and instead generates a message. auto is the default value and means the model can pick between generating a message or calling one or more tools. required means the model must call one or more tools before responding to the user. Specifying a particular tool like {"type": "file_search"} or {"type": "function", "function": {"name": "my_function"}} forces the model to call that tool. |
| [Tools](./tools/) { get; set; } | Gets or sets the list of tools that the assistant used for this run. |
| [TopP](./topp/) { get; set; } | Gets or sets the nucleus sampling value used for this run. If not set, defaults to 1. |
| [TruncationStrategy](./truncationstrategy/) { get; set; } | Gets or sets the truncation strategy that controls for how a thread will be truncated prior to the run. Use this to control the initial context window of the run. |
| [Usage](./usage/) { get; set; } | Gets or sets the usage statistics related to the run. This value will be null if the run is not in a terminal state (i.e. in_progress, queued, etc.). |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

