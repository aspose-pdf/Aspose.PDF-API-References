---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.TruncationStrategy class. Represents the truncation strategy that controls for how a thread will be truncated prior to the run
type: docs
weight: 1240
url: /net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

Represents the truncation strategy that controls for how a thread will be truncated prior to the run.

```csharp
public class TruncationStrategy
```

## Constructors

| Name | Description |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Gets or sets the number of most recent messages from the thread when constructing the context for the run. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Gets or sets the truncation strategy to use for the thread. The default is auto. If set to last_messages, the thread will be truncated to the n most recent messages in the thread. When set to auto, messages in the middle of the thread will be dropped to fit the context length of the model, max_prompt_tokens. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


