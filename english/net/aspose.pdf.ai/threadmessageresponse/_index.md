---
title: "ThreadMessageResponse Class"
linktitle: "ThreadMessageResponse"
articleTitle: "ThreadMessageResponse"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.ThreadMessageResponse class. Represents a message within a thread."
type: docs
weight: 1250
url: "/net/aspose.pdf.ai/threadmessageresponse/"
keywords: "ThreadMessageResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ThreadMessageResponse class

Represents a message within a thread.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageResponse](./threadmessageresponse/#constructor) | Initializes a new instance of the ThreadMessageResponse class. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](./assistantid/) { get; set; } | Gets or sets, if applicable, the ID of the assistant that authored this message. |
| [Attachments](./attachments/) { get; set; } | Gets or sets a list of files attached to the message. |
| [CompletedAt](./completedat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the message was completed. |
| [Content](./content/) { get; set; } | Gets or sets the content of the message in an array of text and/or images. |
| [CreatedAt](./createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the message was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. *(Inherited from BaseResponse)* |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. *(Inherited from BaseResponse)* |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. *(Inherited from BaseResponse)* |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. *(Inherited from BaseResponse)* |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. *(Inherited from BaseResponse)* |
| [Id](./id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. |
| [IncompleteAt](./incompleteat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the message was marked as incomplete. |
| [IncompleteDetails](./incompletedetails/) { get; set; } | Gets or sets an incomplete message, details about why the message is incomplete. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. *(Inherited from BaseResponse)* |
| [Metadata](./metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. *(Inherited from BaseResponse)* |
| [Role](./role/) { get; set; } | Gets or sets the entity that produced the message. One of "user" or "assistant". |
| [RunId](./runid/) { get; set; } | Gets or sets the ID of the run associated with the creation of this message. |
| [Status](./status/) { get; set; } | Gets or sets the status of the message. One of queued , in_progress , requires_action ,. |
| [ThreadId](./threadid/) { get; set; } | Gets or sets the ID of the thread to which this message belongs. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

