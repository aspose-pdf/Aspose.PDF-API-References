---
title: "类 TruncationStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.TruncationStrategy 类。表示在运行前控制线程如何被截断的截断策略。"
type: docs
weight: 1330
url: /zh/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

表示控制线程在运行前如何被截断的截断策略。

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
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | 获取或设置在构建运行上下文时来自线程的最新消息数量。 |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | 获取或设置线程使用的截断策略。默认是 auto。如果设置为 last_messages，线程将截断为最近的 n 条消息。当设置为 auto 时，线程中间的消息将被删除，以适应模型的上下文长度 max_prompt_tokens。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


