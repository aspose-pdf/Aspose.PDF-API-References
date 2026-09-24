---
title: "RunThreadCreateRequest Class"
linktitle: "RunThreadCreateRequest"
articleTitle: "RunThreadCreateRequest"
second_title: "Aspose.PDF for .NET"
description: "Represents a request to create a thread and run it in one request."
type: docs
weight: 1150
url: "/net/aspose.pdf.ai/runthreadcreaterequest/"
keywords: "RunThreadCreateRequest, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## RunThreadCreateRequest class

Represents a request to create a thread and run it in one request.

```csharp
public class RunThreadCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [RunThreadCreateRequest](./runthreadcreaterequest/#constructor) | Initializes a new instance of the RunThreadCreateRequest class. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](./assistantid/) { get; set; } | Gets or sets the ID of the assistant to use to execute this run. |
| [Instructions](./instructions/) { get; set; } | Gets or sets the instructions that override the instructions of the assistant. |
| [MaxCompletionTokens](./maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens that may be used over the course of the run. |
| [MaxPromptTokens](./maxprompttokens/) { get; set; } | Gets or sets the maximum number of prompt tokens that may be used over the course of the run. |
| [Metadata](./metadata/) { get; set; } | Gets or sets set of 16 key-value pairs that can be attached to an object. |
| [Model](./model/) { get; set; } | Gets or sets the ID of the Model to be used to execute this run. If a value is provided here,. |
| [ResponseFormat](./responseformat/) { get; set; } | Gets or sets the format that the model must output. Compatible with GPT-4o, GPT-4 Turbo, and all GPT-3.5 Turbo models since gpt-3.5-turbo-1106. |
| [Stream](./stream/) { get; set; } | Gets or sets if to use streaming. |
| [Temperature](./temperature/) { get; set; } | Gets or sets what sampling temperature to use, between 0 and 2. |
| [Thread](./thread/) { get; set; } | Gets or sets a request to create a thread. |
| [ToolChoice](./toolchoice/) { get; set; } | Gets or sets which (if any) tool is called by the model. none means the model will not call any tools and instead generates a message. |
| [ToolResources](./toolresources/) { get; set; } | Gets or sets a set of resources that are used by the assistant's tools. |
| [Tools](./tools/) { get; set; } | Gets or sets the tools that override the tools the assistant can use for this run. |
| [TopP](./topp/) { get; set; } | Gets or sets a value that alternative to sampling with temperature, called nucleus sampling, where the model considers the results of the tokens with top_p probability mass. |
| [TruncationStrategy](./truncationstrategy/) { get; set; } | Gets or sets the truncation strategy that controls for how a thread will be truncated prior to the run. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

