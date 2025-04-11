---
title: Class Choice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.Choice-Klasse. Stellt eine Wahl in einer Chat-Vervollständigungsantwort dar
type: docs
weight: 200
url: /de/net/aspose.pdf.ai/choice/
---
## Choice-Klasse

Stellt eine Wahl in einer Chat-Vervollständigungsantwort dar.

```csharp
public class Choice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Choice](choice/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FinishReason](../../aspose.pdf.ai/choice/finishreason/) { get; set; } | Ruft den Grund ab oder legt ihn fest, warum das Modell das Generieren von Tokens gestoppt hat. Dies wird gestoppt, wenn das Modell einen natürlichen Stoppunkt oder eine bereitgestellte Stoppsequenz erreicht hat, oder wenn die maximale Anzahl von Tokens, die in der Anfrage angegeben wurde, erreicht wurde. |
| [Index](../../aspose.pdf.ai/choice/index/) { get; set; } | Ruft den Index der Wahl in der Liste der Wahlen ab oder legt ihn fest. |
| [Logprobs](../../aspose.pdf.ai/choice/logprobs/) { get; set; } | Ruft die Log-Wahrscheinlichkeitsinformationen für die Wahl ab oder legt sie fest. |
| [Message](../../aspose.pdf.ai/choice/message/) { get; set; } | Ruft eine vom Modell generierte Chat-Vervollständigungsnachricht ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/choice/tostring/)() | Gibt den Inhalt der Wahl als Zeichenfolge zurück. |

### Siehe auch

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)