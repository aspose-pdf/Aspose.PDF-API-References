---
title: "RunCreateRequest Class"
linktitle: "RunCreateRequest"
articleTitle: "RunCreateRequest"
second_title: "Aspose.PDF for .NET"
description: "Represents a request to create a run."
type: docs
weight: 1060
url: "/net/aspose.pdf.ai/runcreaterequest/"
keywords: "RunCreateRequest, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## RunCreateRequest class

Represents a request to create a run.

```csharp
public class RunCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [RunCreateRequest](./runcreaterequest/#constructor) | Initializes a new instance of the RunCreateRequest class. |

## Properties

| Name | Description |
| --- | --- |
| [AdditionalInstructions](./additionalinstructions/) { get; set; } | Gets or sets the additional instructions. |
| [AdditionalMessages](./additionalmessages/) { get; set; } | Gets or sets the additional messages to the thread before creating the run. |
| [AssistantId](./assistantid/) { get; set; } | Gets or sets the ID of the assistant to use to execute this run. |
| [Instructions](./instructions/) { get; set; } | Gets or sets the instructions that override the instructions of the assistant. This is useful for modifying the behavior on a per-run basis. |
| [MaxCompletionTokens](./maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens that may be used over the course of the run. |
| [MaxPromptTokens](./maxprompttokens/) { get; set; } | Gets or sets the maximum number of prompt tokens that may be used over the course of the run. |
| [Metadata](./metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. |
| [Model](./model/) { get; set; } | Gets or sets the ID of the Model to be used to execute this run. If a value is provided here, it will override the model associated with the assistant. |
| [ResponseFormat](./responseformat/) { get; set; } | Gets or sets the response format. |
| [Stream](./stream/) { get; set; } | Gets or sets if to use streaming. |
| [Temperature](./temperature/) { get; set; } | Gets or sets what sampling temperature to use, between 0 and 2. |
| [ToolChoice](./toolchoice/) { get; set; } | Gets or sets which (if any) tool is called by the model. none means the model will not call any tools and instead generates a message. |
| [Tools](./tools/) { get; set; } | Gets or sets the tools that override the tools the assistant can use for this run. |
| [TopP](./topp/) { get; set; } | Gets or sets an alternative to sampling with temperature, called nucleus sampling,. |
| [TruncationStrategy](./truncationstrategy/) { get; set; } | Gets or sets the truncation strategy. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

