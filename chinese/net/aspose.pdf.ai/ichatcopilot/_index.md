---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.IChatCopilot 接口。表示一个用于通过 AI 模型与文档交互的聊天助手
type: docs
weight: 470
url: /zh/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot 接口

表示一个用于通过 AI 模型与文档交互的聊天助手。

```csharp
public interface IChatCopilot : IAICopilot
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | 异步删除上下文。 |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | 异步获取给定消息列表的响应。 |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | 异步获取给定消息的响应。 |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | 异步将上下文保存到 JSON 文件。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | 异步将给定消息列表的响应保存到 PDF 文件。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | 异步将给定消息的响应保存到 PDF 文件。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | 异步将给定消息列表的响应保存到指定格式的文件。 |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | 异步将给定消息的响应保存到指定格式的文件。 |

### 另请参见

* 接口 [IAICopilot](../iaicopilot/)
* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)