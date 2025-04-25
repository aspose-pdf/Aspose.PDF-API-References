---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunThreadCreateRequest class. Represents a request to create a thread and run it in one request
type: docs
weight: 1150
url: /net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest class

Represents a request to create a thread and run it in one request.

```csharp
public class RunThreadCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | Gets or sets the ID of the assistant to use to execute this run. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | Gets or sets the instructions that override the instructions of the assistant. This is useful for modifying the behavior on a per-run basis. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens that may be used over the course of the run. The run will make a best effort to use only the number of completion tokens specified, across multiple turns of the run. If the run exceeds the number of completion tokens specified, the run will end with status incomplete. See incomplete_details for more info. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | Gets or sets the maximum number of prompt tokens that may be used over the course of the run. The run will make a best effort to use only the number of prompt tokens specified, across multiple turns of the run. If the run exceeds the number of prompt tokens specified, the run will end with status incomplete. See incomplete_details for more info. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | Gets or sets set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | Gets or sets the ID of the Model to be used to execute this run. If a value is provided here, it will override the model associated with the assistant. If not, the model associated with the assistant will be used. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | Gets or sets the format that the model must output. Compatible with GPT-4o, GPT-4 Turbo, and all GPT-3.5 Turbo models since gpt-3.5-turbo-1106. Setting to { "type": "json_object" } enables JSON mode, which guarantees the message the model generates is valid JSON. Important: when using JSON mode, you must also instruct the model to produce JSON yourself via a system or user message. Without this, the model may generate an unending stream of whitespace until the generation reaches the token limit, resulting in a long-running and seemingly "stuck" request. Also note that the message content may be partially cut off if finish_reason="length", which indicates the generation exceeded max_tokens or the conversation exceeded the max context length. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | Gets or sets if to use streaming. If true, returns a stream of events that happen during the Run as server-sent events, terminating when the Run enters a terminal state with a data: [DONE] message. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | Gets or sets what sampling temperature to use, between 0 and 2. Higher values like 0.8 will make the output more random, while lower values like 0.2 will make it more focused and deterministic. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | Gets or sets a request to create a thread. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | Gets or sets which (if any) tool is called by the model. none means the model will not call any tools and instead generates a message. auto is the default value and means the model can pick between generating a message or calling one or more tools. required means the model must call one or more tools before responding to the user. Specifying a particular tool like {"type": "file_search"} or {"type": "function", "function": {"name": "my_function"}} forces the model to call that tool. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | Gets or sets a set of resources that are used by the assistant's tools. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | Gets or sets the tools that override the tools the assistant can use for this run. This is useful for modifying the behavior on a per-run basis. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | Gets or sets a value that alternative to sampling with temperature, called nucleus sampling, where the model considers the results of the tokens with top_p probability mass. So 0.1 means only the tokens comprising the top 10% probability mass are considered. We generally recommend altering this or temperature but not both. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | Gets or sets the truncation strategy that controls for how a thread will be truncated prior to the run. Use this to control the initial context window of the run. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


