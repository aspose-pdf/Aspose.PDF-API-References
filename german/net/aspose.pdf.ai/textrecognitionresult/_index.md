---
title: "Klasse TextRecognitionResult"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "Aspose.Pdf.AI.TextRecognitionResult Klasse. Stellt die aggregierten OCR-Ergebnisse für ein einzelnes Document dar"
type: docs
weight: 1180
url: /de/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

Stellt die aggregierten OCR-Ergebnisse für ein einzelnes Document dar.

```csharp
public class TextRecognitionResult
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | Eine Liste, die die detaillierten OCR-Ergebnisse für jede Page des Document enthält. Bei Einzelbilddateien enthält diese Liste typischerweise einen OcrDetail‑Eintrag mit PageNumber = 1. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | Gibt an, ob OCR für ALLE Pages dieses Document erfolgreich war. False, wenn irgendein OcrDetail in OcrDetails Success = false hat. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | Bezeichner für die Quelldatei (z. B. der vollständige Pfad oder ein eindeutiger Name). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | Eine konsolidierte Fehlermeldung, wenn OverallSuccess false ist, oder eine Zusammenfassung, wenn eine Seite fehlgeschlagen ist. Null, wenn OverallSuccess true ist. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | Liest oder setzt die Gesamtnutzungsstatistiken für die Verarbeitung dieses Document (alle Pages). |

### Siehe auch

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


