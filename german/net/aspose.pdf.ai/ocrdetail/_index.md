---
title: "Klasse OcrDetail"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "Aspose.Pdf.AI.OcrDetail Klasse. Stellt das OCR-Ergebnis für eine einzelne Seite eines Dokuments oder einer einzelnen Bilddatei dar"
type: docs
weight: 860
url: /de/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

Stellt das OCR-Ergebnis für eine einzelne Seite eines Dokuments oder einer einzelnen Bilddatei dar.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [OcrDetail](ocrdetail/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Eine Fehlermeldung, die beschreibt, warum OCR für diese Seite fehlgeschlagen ist, wenn Success false ist. Andernfalls Null. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | Der extrahierte Textinhalt der Seite. Null, wenn Success false ist oder kein Text gefunden wurde. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | Die 1-basierte Page-Nummer im Quell-Dokument. Bei einseitigen Bildern ist sie immer 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | Gibt an, ob die OCR-Extraktion für diese spezifische Page erfolgreich war. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | Liest oder legt die Nutzungsstatistiken fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | Vergleicht die aktuelle OcrDetail-Instanz mit einem anderen OcrDetail-Objekt anhand ihrer PageNumber-Eigenschaft. |

### Siehe auch

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


