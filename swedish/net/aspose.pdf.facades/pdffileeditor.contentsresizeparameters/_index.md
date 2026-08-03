---
title: "Klass PdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters-klass. Klass för att specificera sidändringsparametrar. Tillåter att ange följande parametrar: Storlek på resultatsidan (bredd, höjd) i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vänster, topp, botten och höger marginaler i standardenhetsmått eller i procent av den ursprungliga sidans storlek. Vissa värden kan lämnas null för automatisk beräkning. Dessa värden beräknas från återstående sidstorlek efter att uttryckligen angivna värden har beräknats. Till exempel, om sidbredd = 100 och ny sidbredd anges till 60 enheter, beräknas vänster- och högermarginalerna automatiskt: (100 - 60) / 2 = 15. Denna klass används i metoden ResizeContents."
type: docs
weight: 4600
url: /sv/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Klass för att specificera sidändringsparametrar. Tillåter att ange följande parametrar: Storlek på resultatsidan (bredd, höjd) i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vänster, topp, botten och höger marginaler i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden beräknas från återstående sidstorlek efter att uttryckligen angivna värden har beräknats. Till exempel: om sidbredd = 100 och ny sidbredd anges till 60 enheter, beräknas vänster- och högermarginalerna automatiskt: (100 - 60) / 2 = 15. Denna klass används i metoden ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Skapar ändringsparametrar där alla värden är satta till "auto". Senare kan marginaler och innehållsstorlek specificeras om så krävs. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Skapar ändringsparametrar med angivna marginalvärden och innehållsstorlek. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Hämtar eller anger bottenmarginal på den resulterande sidan. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Hämtar eller anger höjden på innehållet från källsidan på den resulterande sidan. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Hämtar eller anger bredden på innehållet från källsidan på den resulterande sidan. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Hämtar eller anger vänstermarginal på den resulterande sidan. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Hämtar eller anger högermarginal på den resulterande sidan. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Hämtar eller anger toppmarginal på den resulterande sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Skapar ändringsparametrar med angiven innehållsstorlek. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Skapar ändringsparametrar med angiven innehållsstorlek i procent av den ursprungliga sidans storlek. Marginalerna beräknas automatiskt. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Skapar ändringsparametrar med specificerade marginalvärden. Innehållsstorleken beräknas automatiskt. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Skapar ändringsparametrar. Marginalerna anges i procent av den ursprungliga sidans storlek. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Skapar ändringsparametrar för sidändring. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Skapar ändringsparametrar för sidändring. Nya storlekar anges i procent. |

### Se även

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


