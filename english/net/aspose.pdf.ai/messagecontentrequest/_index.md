---
title: "MessageContentRequest Class"
linktitle: "MessageContentRequest"
articleTitle: "MessageContentRequest"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.MessageContentRequest class. The content of the message in array of text and/or images."
type: docs
weight: 830
url: "/net/aspose.pdf.ai/messagecontentrequest/"
keywords: "MessageContentRequest, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## MessageContentRequest class

The content of the message in array of text and/or images.

```csharp
public class MessageContentRequest : MessageContentBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MessageContentRequest](./messagecontentrequest/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ImageFile](../../aspose.pdf.ai/messagecontentbase/imagefile/) { get; set; } | Gets or sets an image File in the content of a message. *(Inherited from MessageContentBase)* |
| [ImageUrl](../../aspose.pdf.ai/messagecontentbase/imageurl/) { get; set; } | Gets or sets an image URL in the content of a message. *(Inherited from MessageContentBase)* |
| [MessageContentType](../../aspose.pdf.ai/messagecontentbase/messagecontenttype/) { get; set; } | Gets or sets the type of content. *(Inherited from MessageContentBase)* |
| [Text](./text/) { get; set; } | Gets or sets the text content that is part of a message. |

## Methods

| Name | Description |
| --- | --- |
| [CreateImageFileContent](./createimagefilecontent/)(*string, string*) | Creates an image file content for a message. |
| [CreateImageUrlContent](./createimageurlcontent/)(*string, string*) | Creates an image URL content for a message. |
| [CreateTextContent](./createtextcontent/)(*string*) | Creates a text content for a message. |

### See Also

* class [MessageContentBase](../messagecontentbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

