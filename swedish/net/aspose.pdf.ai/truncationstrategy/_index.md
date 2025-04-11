---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.TruncationStrategy klass. Representerar trunceringsstrategin som kontrollerar hur en tråd kommer att trunkeras före körningen
type: docs
weight: 1240
url: /sv/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy klass

Representerar trunceringsstrategin som kontrollerar hur en tråd kommer att trunkeras före körningen.

```csharp
public class TruncationStrategy
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Hämtar eller ställer in antalet senaste meddelanden från tråden när kontexten för körningen konstrueras. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Hämtar eller ställer in trunceringsstrategin som ska användas för tråden. Standard är auto. Om den sätts till last_messages, kommer tråden att trunkeras till de n senaste meddelandena i tråden. När den sätts till auto, kommer meddelanden i mitten av tråden att tas bort för att passa kontextlängden för modellen, max_prompt_tokens. |

### Se Även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)