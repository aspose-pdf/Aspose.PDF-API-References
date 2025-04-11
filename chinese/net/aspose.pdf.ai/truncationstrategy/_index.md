---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.TruncationStrategy 类。表示控制线程在运行之前如何被截断的截断策略
type: docs
weight: 1240
url: /zh/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy 类

表示控制线程在运行之前如何被截断的截断策略。

```csharp
public class TruncationStrategy
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | 获取或设置构建运行上下文时线程中最近的消息数量。 |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | 获取或设置用于线程的截断策略。默认值为 auto。如果设置为 last_messages，线程将被截断为线程中最近的 n 条消息。当设置为 auto 时，线程中间的消息将被丢弃以适应模型的上下文长度 max_prompt_tokens。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)