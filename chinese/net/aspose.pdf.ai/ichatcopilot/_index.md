---
title: "接口 IChatCopilot"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.IChatCopilot 接口。表示用于通过 AI 模型与文档交互的聊天副驾驶。"
type: docs
weight: 490
url: /zh/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot interface

表示通过 AI 模型与文档交互的聊天副驾驶。

```csharp
public interface IChatCopilot : IAICopilot
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | 异步删除上下文。 |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | 异步获取给定消息列表的响应。 |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | 异步获取给定消息的响应。 |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | 异步将上下文保存为 JSON 文件。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | 异步将给定消息列表的响应保存为 PDF 文件。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | 异步将给定消息的响应保存为 PDF 文件。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | 异步将给定消息列表的响应保存为指定格式的文件。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | 异步将给定消息的响应保存为指定格式的文件。 |

### 另请参见

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


