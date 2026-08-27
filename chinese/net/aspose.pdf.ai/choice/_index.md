---
title: "类 Choice"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.Choice 类。表示聊天完成响应中的一个选项"
type: docs
weight: 210
url: /zh/net/aspose.pdf.ai/choice/
---
## Choice class

表示聊天完成响应中的一个选项。

```csharp
public class Choice
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Choice](choice/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FinishReason](../../aspose.pdf.ai/choice/finishreason/) { get; set; } | 获取或设置模型停止生成标记的原因。如果模型达到自然停止点或提供的停止序列，则为 stop；如果请求中指定的最大标记数已达到，则为 length。 |
| [Index](../../aspose.pdf.ai/choice/index/) { get; set; } | 获取或设置选项在选项列表中的索引。 |
| [Logprobs](../../aspose.pdf.ai/choice/logprobs/) { get; set; } | 获取或设置该选项的对数概率信息。 |
| [Message](../../aspose.pdf.ai/choice/message/) { get; set; } | 获取或设置模型生成的聊天完成消息。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/choice/tostring/)() | 以字符串形式返回选项的内容。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


