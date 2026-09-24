---
title: "CompletionCreateRequest Class"
linktitle: "CompletionCreateRequest"
articleTitle: "CompletionCreateRequest"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.CompletionCreateRequest class. Represents a request for the Create Chat Completion endpoint."
type: docs
weight: 210
url: "/net/aspose.pdf.ai/completioncreaterequest/"
keywords: "CompletionCreateRequest, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## CompletionCreateRequest class

Represents a request for the Create Chat Completion endpoint.

```csharp
public class CompletionCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [CompletionCreateRequest](./completioncreaterequest/#constructor) | Initializes a new instance of the CompletionCreateRequest class. |

## Properties

| Name | Description |
| --- | --- |
| [FrequencyPenalty](./frequencypenalty/) { get; set; } | Gets or sets a number between -2.0 and 2.0. |
| [LogitBias](./logitbias/) { get; set; } | Gets or sets the likelihood of specified tokens appearing in the completion. |
| [Logprobs](./logprobs/) { get; set; } | Gets or sets whether to return log probabilities of the output tokens or not. |
| [MaxCompletionTokens](./maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of tokens to generate in the completion. |
| [Messages](./messages/) { get; set; } | Gets or sets a list of messages comprising the conversation so far. |
| [Model](./model/) { get; set; } | Gets or sets the ID of the model to use. |
| [NumberOfChoices](./numberofchoices/) { get; set; } | Gets or sets how many chat completion choices to generate for each input message. Note that you will be charged based on the number of generated. |
| [PresencePenalty](./presencepenalty/) { get; set; } | Gets or sets number between -2.0 and 2.0. Positive values penalize new tokens based on whether they appear in the text so far, increasing. |
| [ResponseFormat](./responseformat/) { get; set; } | Gets or sets an object specifying the format that the model must output. |
| [Seed](./seed/) { get; set; } | Gets or sets the Seed value. |
| [Stop](./stop/) { get; set; } | Gets or sets up to 4 sequences where the API will stop generating further tokens. |
| [Stream](./stream/) { get; set; } | Gets or sets if to use streaming. |
| [Temperature](./temperature/) { get; set; } | Gets or sets what sampling temperature to use, between 0 and 2. |
| [ToolChoice](./toolchoice/) { get; set; } | Gets or sets an object that controls which (if any) tool is called by the model. |
| [Tools](./tools/) { get; set; } | Gets or sets a list of tools the model may call. Currently, only functions are supported as a tool. |
| [TopP](./topp/) { get; set; } | Gets or sets an alternative to sampling with temperature, called nucleus sampling, where the model considers the results. |
| [User](./user/) { get; set; } | Gets or sets a unique identifier representing your end-user, which can help OpenAI to monitor and detect abuse. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

