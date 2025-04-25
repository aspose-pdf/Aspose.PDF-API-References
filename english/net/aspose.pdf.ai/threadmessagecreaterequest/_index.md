---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageCreateRequest class. Represents a request to create a message within a thread
type: docs
weight: 1210
url: /net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest class

Represents a request to create a message within a thread.

```csharp
public class ThreadMessageCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Gets or sets a list of files attached to the message. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Gets or sets the content of the message. Can be a string or an array of content parts. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Gets or sets the role of the entity creating the message. Allowed values include: "user", "assistant". |

## Methods

| Name | Description |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Creates a new `ThreadMessageCreateRequest` with the role set to Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Creates a new `ThreadMessageCreateRequest` with the role set to User. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Sets the attachments for the thread message request. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Adds a message content to the thread message request. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Sets the message contents for the thread message request. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Sets the metadata for the thread message request. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


