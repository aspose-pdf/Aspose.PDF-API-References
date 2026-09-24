---
title: "ThreadMessageCreateRequest Class"
linktitle: "ThreadMessageCreateRequest"
articleTitle: "ThreadMessageCreateRequest"
second_title: "Aspose.PDF for .NET"
description: "Represents a request to create a message within a thread."
type: docs
weight: 1210
url: "/net/aspose.pdf.ai/threadmessagecreaterequest/"
keywords: "ThreadMessageCreateRequest, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ThreadMessageCreateRequest class

Represents a request to create a message within a thread.

```csharp
public class ThreadMessageCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageCreateRequest](./threadmessagecreaterequest/#constructor) | Initializes a new instance of the ThreadMessageCreateRequest class. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](./attachments/) { get; set; } | Gets or sets a list of files attached to the message. |
| [Content](./content/) { get; set; } | Gets or sets the content of the message. Can be a string or an array of content parts. |
| [Metadata](./metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. |
| [Role](./role/) { get; set; } | Gets or sets the role of the entity creating the message. |

## Methods

| Name | Description |
| --- | --- |
| [FromAssistant](./fromassistant/) | Creates a new [`ThreadMessageCreateRequest`](../../aspose.pdf.ai/threadmessagecreaterequest/) with the role set to Assistant. |
| [FromUser](./fromuser/) | Creates a new [`ThreadMessageCreateRequest`](../../aspose.pdf.ai/threadmessagecreaterequest/) with the role set to User. |
| [WithAttachments](./withattachments/)(*List<Attachment>*) | Sets the attachments for the thread message request. |
| [WithContent](./withcontent/)(*MessageContentRequest*) | Adds a message content to the thread message request. |
| [WithContents](./withcontents/)(*List<MessageContentRequest>*) | Sets the message contents for the thread message request. |
| [WithMetadata](./withmetadata/)(*Dictionary<string, string>*) | Sets the metadata for the thread message request. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

