---
title: "AssistantModifyRequest Class"
linktitle: "AssistantModifyRequest"
articleTitle: "AssistantModifyRequest"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.AssistantModifyRequest class. Request object for modifying an assistant."
type: docs
weight: 100
url: "/net/aspose.pdf.ai/assistantmodifyrequest/"
keywords: "AssistantModifyRequest, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## AssistantModifyRequest class

Request object for modifying an assistant.

```csharp
public class AssistantModifyRequest : AssistantCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [AssistantModifyRequest](./assistantmodifyrequest/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Gets or sets the description of the assistant. The maximum length is 512 characters. *(Inherited from AssistantCreateRequest)* |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Gets or sets the system instructions that the assistant uses. The maximum length is 256,000. *(Inherited from AssistantCreateRequest)* |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing. *(Inherited from AssistantCreateRequest)* |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Gets or sets ID of the model to use. You can use the List models API to see all of your available. *(Inherited from AssistantCreateRequest)* |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Gets or sets the name of the assistant. The maximum length is 256 characters. *(Inherited from AssistantCreateRequest)* |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Gets or sets the format that the model must output. Compatible with GPT-4o, GPT-4 Turbo, and all GPT-3.5 Turbo models since gpt-3.5-turbo-1106 . *(Inherited from AssistantCreateRequest)* |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Gets or sets sampling temperature to use, between 0 and 2. Higher values like 0.8 will make the. *(Inherited from AssistantCreateRequest)* |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Gets or sets resources that are used by the assistant's tools. The resources are specific to. *(Inherited from AssistantCreateRequest)* |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Gets or sets a list of tool enabled on the assistant. There can be a maximum of 128 tools per. *(Inherited from AssistantCreateRequest)* |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Gets or sets an alternative to sampling with temperature, called nucleus sampling, where the model. *(Inherited from AssistantCreateRequest)* |

### See Also

* class [AssistantCreateRequest](../assistantcreaterequest/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

