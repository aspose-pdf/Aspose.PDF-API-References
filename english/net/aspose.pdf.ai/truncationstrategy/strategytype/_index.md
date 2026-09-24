---
title: "TruncationStrategy.StrategyType"
linktitle: "StrategyType"
articleTitle: "StrategyType"
second_title: "Aspose.PDF for .NET API Reference"
description: "TruncationStrategy property. Gets or sets the truncation strategy to use for the thread. The default is auto. If set to last_messages, the thread will be tru..."
type: docs
weight: 20
url: "/net/aspose.pdf.ai/truncationstrategy/strategytype/"
product_version: "26.9.0"
---
## TruncationStrategy.StrategyType property

Gets or sets the truncation strategy to use for the thread.
 The default is auto.
 If set to last_messages, the thread will be truncated to the n most recent messages in the thread.
 When set to auto, messages in the middle of the thread will be dropped to fit the context length of the model, max_prompt_tokens.

```csharp
public string StrategyType { get; set; }
```

### Property Value

string

### See Also

* class [TruncationStrategy](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

