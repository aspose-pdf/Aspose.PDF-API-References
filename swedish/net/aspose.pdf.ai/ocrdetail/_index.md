---
title: "Klass OcrDetail"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OcrDetail klass. Representerar OCR‑resultatet för en enskild page i ett document eller en enskild bildfil"
type: docs
weight: 860
url: /sv/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

Representerar OCR-resultatet för en enskild sida i ett dokument eller en enskild bildfil.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OcrDetail](ocrdetail/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Ett felmeddelande som beskriver varför OCR misslyckades för denna page, om Success är falskt. Null annars. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | Den extraherade textinnehållet från page. Null om Success är falskt eller ingen text hittades. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | Det 1‑baserade page‑numret inom source document. För single-page images kommer detta alltid att vara 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | Indikerar om OCR‑extraktionen för denna specifika page var framgångsrik. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | Hämtar eller anger användningsstatistiken. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | Jämför den aktuella OcrDetail‑instansen med ett annat OcrDetail‑objekt baserat på deras PageNumber‑egenskap. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


