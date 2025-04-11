---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Drawing.Graph klass. Representerar graf - grafikgenerator paragraf
type: docs
weight: 3940
url: /sv/net/aspose.pdf.drawing/graph/
---
## Graf klass

Representerar graf - grafikgenerator paragraf.

```csharp
public sealed class Graph : BaseParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | Initierar en ny instans av `Graph` klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | Hämtar eller ställer in gränsen. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Hämtar eller ställer in ett [`GraphInfo`](./graphinfo/) objekt som indikerar grafens information, såsom färg, linjebredd, etc. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Hämtar eller ställer in ett flyttal som indikerar grafens höjd. Enheten är punkt. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller ställer in en horisontell justering av paragrafen |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Hämtar eller ställer in ändra nuvarande position efter att ha bearbetat paragrafen. (standard är true) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om denna paragraf kommer att vara i nästa kolumn. Standard är false. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om en paragraf är inline. Standard är false. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar denna paragraf att genereras på en ny sida. Standard är false. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om den aktuella paragrafen förblir på samma sida tillsammans med nästa paragraf. Standard är false. (för pdf-generering) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Hämtar eller ställer in tabellens vänstra koordinat. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för paragrafen (för pdf-generering) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Hämtar eller ställer in en [`Shapes`](./shapes/) samling som indikerar alla former i grafen. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Hämtar eller ställer in ett strängvärde som indikerar titeln på grafen. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Hämtar eller ställer in tabellens övre koordinat. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av paragrafen |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Hämtar eller ställer in ett flyttal som indikerar grafens bredd. Enheten är punkt. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Klona grafen. |

### Se Även

* klass [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namnrymd [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)