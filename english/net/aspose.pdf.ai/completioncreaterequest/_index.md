---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionCreateRequest class. Represents a request for the Create Chat Completion endpoint
type: docs
weight: 220
url: /net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

Represents a request for the Create Chat Completion endpoint.

```csharp
public class CompletionCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Gets or sets a number between -2.0 and 2.0. Positive values penalize new tokens based on their existing frequency in the text so far, decreasing the model's likelihood to repeat the same line verbatim. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Gets or sets the likelihood of specified tokens appearing in the completion. Accepts a JSON object that maps tokens (specified by their token ID in the tokenizer) to an associated bias value from -100 to 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Gets or sets whether to return log probabilities of the output tokens or not. If true, returns the log probabilities of each output token returned in the content of the message. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | Gets or sets the maximum number of tokens to generate in the completion. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Gets or sets a list of messages comprising the conversation so far. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Gets or sets the ID of the model to use. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Gets or sets how many chat completion choices to generate for each input message. Note that you will be charged based on the number of generated tokens across all of the choices. Keep n as 1 to minimize costs. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Gets or sets number between -2.0 and 2.0. Positive values penalize new tokens based on whether they appear in the text so far, increasing the model's likelihood to talk about new topics. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Gets or sets an object specifying the format that the model must output. Compatible with GPT-4 Turbo and all GPT-3.5 Turbo models newer than gpt-3.5-turbo-1106. Setting to { "type": "json_object" } enables JSON mode, which guarantees the message the model generates is valid JSON. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Gets or sets the Seed value. This feature is in Beta. If specified, our system will make a best effort to sample deterministically, such that repeated requests with the same seed and parameters should return the same result. Determinism is not guaranteed, and you should refer to the system_fingerprint response parameter to monitor changes in the backend. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Gets or sets up to 4 sequences where the API will stop generating further tokens. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Gets or sets if to use streaming. If set, partial message deltas will be sent, like in ChatGPT. Tokens will be sent as data-only server-sent events as they become available, with the stream terminated by a data: [DONE] message. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Gets or sets what sampling temperature to use, between 0 and 2. Higher values like 0.8 will make the output more random, while lower values like 0.2 will make it more focused and deterministic. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Gets or sets an object that controls which (if any) tool is called by the model. none means the model will not call any tool and instead generates a message. auto means the model can pick between generating a message or calling one or more tools. required means the model must call one or more tools. Specifying a particular tool via {"type": "function", "function": {"name": "my_function"}} forces the model to call that tool. none is the default when no tools are present.auto is the default if tools are present. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Gets or sets a list of tools the model may call. Currently, only functions are supported as a tool. Use this to provide a list of functions the model may generate JSON inputs for. A max of 128 functions are supported. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Gets or sets an alternative to sampling with temperature, called nucleus sampling, where the model considers the results of the tokens with top_p probability mass. So 0.1 means only the tokens comprising the top 10% probability mass are considered. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Gets or sets a unique identifier representing your end-user, which can help OpenAI to monitor and detect abuse. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


