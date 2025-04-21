---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters klass. Klass för att specificera sidominskningsparametrar. Möjliggör att ställa in följande parametrar Storlek på resulterande sida i standard rumsenheter eller i procent av den ursprungliga sidans storlek; Vänster, Topp, Botten och Höger marginaler i standard rumsenheter eller i procent av den ursprungliga sidans storlek; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden kommer att beräknas från resten av sidans storlek efter att de explicit angivna värdena har beräknats. Denna klass används i ResizeContents-metoden.
type: docs
weight: 4480
url: /sv/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters klass

Klass för att specificera sidominskningsparametrar. Möjliggör att ställa in följande parametrar: Storlek på resulterande sida (bredd, höjd) i standard rumsenheter eller i procent av den ursprungliga sidans storlek; Vänster, Topp, Botten och Höger marginaler i standard rumsenheter eller i procent av den ursprungliga sidans storlek; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden kommer att beräknas från resten av sidans storlek efter att de explicit angivna värdena har beräknats. Till exempel: om sidans bredd = 100 och ny sidbredd anges till 60 enheter, då beräknas vänster och höger marginaler automatiskt: (100 - 60) / 2 = 15. Denna klass används i ResizeContents-metoden.

```csharp
public class ContentsResizeParameters
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Skapar minskningsparametrar där alla värden är inställda på "auto". Senare kan marginaler och innehållsstorlek specificeras om det behövs. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Skapar minskningsparametrar med specificerade marginalvärden och innehållsstorlek. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Hämtar eller ställer in bottenmarginalen på den resulterande sidan. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Hämtar eller ställer in höjden på innehållet på källsidan på den resulterande sidan. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Hämtar eller ställer in bredden på innehållet på källsidan på den resulterande sidan. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Hämtar eller ställer in vänstermarginalen på den resulterande sidan. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Hämtar eller ställer in högermarginalen på den resulterande sidan. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Hämtar eller ställer in toppmarginalen på den resulterande sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Skapar minskningsparametrar med specificerad innehållsstorlek. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Skapar minskningsparametrar med specificerad innehållsstorlek i procent av den ursprungliga sidans storlek. Marginaler beräknas automatiskt. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Skapar minskningsparametrar med specificerade marginalvärden. Innehållsstorleken beräknas automatiskt. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Skapar minskningsparametrar. Marginaler anges i procent av den ursprungliga sidans storlek. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Skapar minskningsparametrar för sidominskning. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Skapar minskningsparametrar för sidominskning. Nya storlekar anges i procent. |

### Se Även

* klass [PdfFileEditor](../pdffileeditor/)
* namnrum [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../)