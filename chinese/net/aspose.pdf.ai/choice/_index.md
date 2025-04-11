---
title: Class Choice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.Choice 类。表示聊天完成响应中的一个选择
type: docs
weight: 200
url: /zh/net/aspose.pdf.ai/choice/
---
## Choice 类

表示聊天完成响应中的一个选择。

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
| [FinishReason](../../aspose.pdf.ai/choice/finishreason/) { get; set; } | 获取或设置模型停止生成令牌的原因。如果模型达到自然停止点或提供的停止序列，或者请求中指定的最大令牌数达到，则会停止。 |
| [Index](../../aspose.pdf.ai/choice/index/) { get; set; } | 获取或设置选择在选择列表中的索引。 |
| [Logprobs](../../aspose.pdf.ai/choice/logprobs/) { get; set; } | 获取或设置选择的对数概率信息。 |
| [Message](../../aspose.pdf.ai/choice/message/) { get; set; } | 获取或设置模型生成的聊天完成消息。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/choice/tostring/)() | 返回选择的内容作为字符串。 |

### 另见

* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)