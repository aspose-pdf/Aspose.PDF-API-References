---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantResponse 类。表示一个可以调用模型并使用工具的助手
type: docs
weight: 140
url: /zh/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse 类

表示一个可以调用模型并使用工具的助手。

```csharp
public class AssistantResponse : BaseResponse
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | 获取或设置助手创建时的 Unix 时间戳（以秒为单位）。 |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | 获取或设置助手的描述。最大长度为 512 个字符。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详细信息。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态码。 |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | 获取或设置标识符，可以在 API 端点中引用。 |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | 获取或设置助手使用的系统指令。最大长度为 256,000 个字符。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | 获取或设置一组 16 个键值对，可以附加到对象上。这对于以结构化格式存储有关对象的附加信息非常有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | 获取或设置要使用的模型 ID。您可以使用列出模型 API 查看所有可用模型，或查看我们的模型概述以获取描述。 |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | 获取或设置助手的名称。最大长度为 256 个字符。 |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | 获取或设置对象类型，始终为助手。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | 获取或设置模型必须输出的格式。与 GPT-4o、GPT-4 Turbo 和自 gpt-3.5-turbo-1106 以来的所有 GPT-3.5 Turbo 模型兼容。设置为 { "type": "json_object" } 启用 JSON 模式，确保模型生成的消息是有效的 JSON。重要提示：在使用 JSON 模式时，您还必须通过系统或用户消息指示模型生成 JSON。否则，模型可能会生成无尽的空白流，直到生成达到令牌限制，导致请求长时间运行并似乎“卡住”。还请注意，如果 finish_reason="length"，消息内容可能会部分被截断，这表示生成超过了 max_tokens 或对话超过了最大上下文长度。 |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | 获取或设置要使用的采样温度，范围在 0 到 2 之间。较高的值如 0.8 会使输出更随机，而较低的值如 0.2 会使其更集中和确定。 |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | 获取或设置助手工具使用的一组资源。资源特定于工具类型。例如，code_interpreter 工具需要文件 ID 列表，而 file_search 工具需要向量存储 ID 列表。 |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | 获取或设置助手启用的工具列表。每个助手最多可以有 128 个工具。工具可以是 code_interpreter、file_search 或 function 类型。 |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | 获取或设置一种替代温度采样的方法，称为核采样，其中模型考虑具有 top_p 概率质量的令牌结果。因此 0.1 意味着仅考虑组成前 10% 概率质量的令牌。我们通常建议更改此值或温度，但不要同时更改两者。 |

### 另请参见

* 类 [BaseResponse](../baseresponse/)
* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)