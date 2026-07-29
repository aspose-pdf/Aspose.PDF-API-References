---
title: "类 ChatMessage"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.ChatMessage 类。模型生成的聊天完成消息"
type: docs
weight: 190
url: /zh/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage class

模型生成的聊天完成消息。

```csharp
public class ChatMessage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | 初始化 `ChatMessage` 类的新实例。 |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | 初始化 `ChatMessage` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | 获取或设置消息的内容。 |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | 获取或设置参与者的可选名称。提供模型信息以区分具有相同角色的参与者。 |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | 获取或设置消息作者的角色。 |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | 获取或设置此消息响应的工具调用。 |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | 获取或设置模型生成的工具调用，例如函数调用。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | 创建一个表示助理消息的新的 ChatMessage 对象。 |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | 创建一个表示系统消息的新的 ChatMessage 对象。 |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | 创建一个表示用户消息的新的 ChatMessage 对象。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


