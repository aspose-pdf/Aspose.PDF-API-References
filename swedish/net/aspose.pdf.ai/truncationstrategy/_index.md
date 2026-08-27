---
title: "Klass TruncationStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.TruncationStrategy-klass. Representerar trunkeringsstrategin som styr hur en tråd kommer att trunkeras före körningen"
type: docs
weight: 1330
url: /sv/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

Representerar trunkeringsstrategin som styr hur en tråd kommer att trunkeras före körningen.

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
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Hämtar eller anger antalet senaste meddelanden från tråden när kontexten för körningen byggs. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Hämtar eller anger trunkeringsstrategin som ska användas för tråden. Standard är auto. Om den sätts till last_messages kommer tråden att trunkeras till de n senaste meddelandena i tråden. När den sätts till auto kommer meddelanden i mitten av tråden att tas bort för att passa modellens kontextlängd, max_prompt_tokens. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


