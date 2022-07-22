---
title: Heading
second_title: Aspose.PDF för .NET API Referens
description: Representerar rubrik.
type: docs
weight: 3360
url: /sv/net/aspose.pdf/heading/
---
## Heading class

Representerar rubrik.

```csharp
public sealed class Heading : TextFragment
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Heading](heading)(int) | Initierar en ny instans av klassen Cell. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Får textposition för text, representerad med[`TextFragment`](../../aspose.pdf.text/textfragment) object. YIndent av positionsstrukturen representerar baslinjekoordinaten för textfragmentet. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage) { get; set; } | Hämtar målsidan. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Hämtar eller ställer in styckeslutnoten.(endast för pdf-generering) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Hämtar eller ställer in styckets fotnot.(endast för pdf-generering) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Hämtar formulärobjekt som innehåller TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Hämtar eller ställer in en horisontell justering av textfragment. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Ställer in fragmentets hyperlänk |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence) { get; set; } | Hämtar rubriken ska numreras automatiskt. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om detta stycke kommer att finnas i nästa kolumn. Standard är falskt.(för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Hämtar eller ställer in ett stycke inline. Standard är falskt.(för pdf-generering) |
| [IsInList](../../aspose.pdf/heading/isinlist) { get; set; } | Får rubriken bör finnas i toc-listan. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Hämtar eller ställer in ett boolvärde som tvingar fram detta stycke vid ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om det aktuella stycket finns kvar på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Level](../../aspose.pdf/heading/level) { get; set; } | Får nivån. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Hämtar eller ställer in en yttre marginal för stycke (för pdf-generering) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Hämtar sida som innehåller TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Hämtar eller ställer in textposition för text, representerad med[`TextFragment`](../../aspose.pdf.text/textfragment) objekt. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Får rektangel av TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Får textersättningsalternativ. Alternativen definierar beteende när fragmenterad text ersätts till mer kort/lång. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Hämtar textsegment för nuvarande[`TextFragment`](../../aspose.pdf.text/textfragment) . |
| [StartNumber](../../aspose.pdf/heading/startnumber) { get; set; } | Får rubrikens startnummer. |
| [Style](../../aspose.pdf/heading/style) { get; set; } | Får eller sätter stil. |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Hämtar eller sätterString textobjekt som[`TextFragment`](../../aspose.pdf.text/textfragment) objekt representerar. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Hämtar eller ställer in texttillstånd för texten som[`TextFragment`](../../aspose.pdf.text/textfragment) objekt representerar. |
| [TocPage](../../aspose.pdf/heading/tocpage) { get; set; } | Hämtar sidan som innehåller denna rubrik. |
| [Top](../../aspose.pdf/heading/top) { get; set; } | Får det översta Y av dessa rubriker. |
| [UserLabel](../../aspose.pdf/heading/userlabel) { get; set; } | Hämtar eller ställer in användaretikett. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av textfragment. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Hämtar eller ställer in radbrytningsantal för detta stycke (endast för pdf-generering) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone)() | Klona rubriken. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments)() | Klona rubriken med alla segment. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Blir[`TextSegment`](../../aspose.pdf.text/textsegment) (s) representerar specificerad del av[`TextFragment`](../../aspose.pdf.text/textfragment) text. |

### Se även

* class [TextFragment](../../aspose.pdf.text/textfragment)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
