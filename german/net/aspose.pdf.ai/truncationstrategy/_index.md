---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.TruncationStrategy-Klasse. Stellt die Truncation-Strategie dar, die steuert, wie ein Thread vor dem Lauf gekürzt wird.
type: docs
weight: 1240
url: /de/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy-Klasse

Stellt die Truncation-Strategie dar, die steuert, wie ein Thread vor dem Lauf gekürzt wird.

```csharp
public class TruncationStrategy
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Ruft die Anzahl der aktuellsten Nachrichten aus dem Thread ab oder legt sie fest, wenn der Kontext für den Lauf erstellt wird. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Ruft die Truncation-Strategie ab oder legt sie fest, die für den Thread verwendet werden soll. Der Standardwert ist auto. Wenn auf last_messages gesetzt, wird der Thread auf die n aktuellsten Nachrichten im Thread gekürzt. Wenn auf auto gesetzt, werden Nachrichten in der Mitte des Threads verworfen, um die Kontextlänge des Modells, max_prompt_tokens, anzupassen. |

### Siehe auch

* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)