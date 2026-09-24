---
title: "AssistantCreateRequest Class"
linktitle: "AssistantCreateRequest"
articleTitle: "AssistantCreateRequest"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.AssistantCreateRequest class. Request object for creating an assistant."
type: docs
weight: 70
url: "/net/aspose.pdf.ai/assistantcreaterequest/"
keywords: "AssistantCreateRequest, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## AssistantCreateRequest class

Request object for creating an assistant.

```csharp
public class AssistantCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [AssistantCreateRequest](./assistantcreaterequest/#constructor) | Initializes a new instance of the AssistantCreateRequest class. |

## Properties

| Name | Description |
| --- | --- |
| [Description](./description/) { get; set; } | Gets or sets the description of the assistant. The maximum length is 512 characters. |
| [Instructions](./instructions/) { get; set; } | Gets or sets the system instructions that the assistant uses. The maximum length is 256,000. |
| [Metadata](./metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing. |
| [Model](./model/) { get; set; } | Gets or sets ID of the model to use. You can use the List models API to see all of your available. |
| [Name](./name/) { get; set; } | Gets or sets the name of the assistant. The maximum length is 256 characters. |
| [ResponseFormat](./responseformat/) { get; set; } | Gets or sets the format that the model must output. Compatible with GPT-4o, GPT-4 Turbo, and all GPT-3.5 Turbo models since gpt-3.5-turbo-1106 . |
| [Temperature](./temperature/) { get; set; } | Gets or sets sampling temperature to use, between 0 and 2. Higher values like 0.8 will make the. |
| [ToolResources](./toolresources/) { get; set; } | Gets or sets resources that are used by the assistant's tools. The resources are specific to. |
| [Tools](./tools/) { get; set; } | Gets or sets a list of tool enabled on the assistant. There can be a maximum of 128 tools per. |
| [TopP](./topp/) { get; set; } | Gets or sets an alternative to sampling with temperature, called nucleus sampling, where the model. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

