---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageResponse class. Represents a message within a thread
type: docs
weight: 1250
url: /net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

Represents a message within a thread.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Gets or sets, if applicable, the ID of the assistant that authored this message. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Gets or sets a list of files attached to the message. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the message was completed. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Gets or sets the content of the message in an array of text and/or images. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the message was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the message was marked as incomplete. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Gets or sets an incomplete message, details about why the message is incomplete. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Gets or sets the object type, which is always "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Gets or sets the entity that produced the message. One of "user" or "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Gets or sets the ID of the run associated with the creation of this message. Value is null when messages are created manually. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Gets or sets the status of the message. One of queued , in_progress , requires_action , or completed . |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Gets or sets the ID of the thread to which this message belongs. |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


