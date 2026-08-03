---
title: "Klass TextRecognitionResult"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.TextRecognitionResult-klass. Representerar de aggregerade OCR-resultaten för ett enskilt källdokument"
type: docs
weight: 1180
url: /sv/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

Representerar de aggregerade OCR-resultaten för ett enskilt källdokument.

```csharp
public class TextRecognitionResult
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | En lista som innehåller de detaljerade OCR-resultaten för varje sida i dokumentet. För enkelsbildsfiler kommer denna lista vanligtvis att innehålla en OcrDetail-post med PageNumber = 1. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | Anger om OCR var framgångsrik för ALLA sidor i detta dokument. Falskt om någon OcrDetail i OcrDetails har Success = false. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | Identifierare för källfilen (t.ex. hela sökvägen eller ett unikt namn). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | Ett konsoliderat felmeddelande om OverallSuccess är falskt, eller en sammanfattning om någon sida misslyckades. Null om OverallSuccess är sant. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | Hämtar eller anger den totala användningsstatistiken för bearbetning av detta dokument (alla sidor). |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


