---
title: "Klass Heading"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Heading-klass. Representerar rubrik."
type: docs
weight: 5590
url: /sv/net/aspose.pdf/heading/
---
## Heading class

Representerar rubrik.

```csharp
public sealed class Heading : TextFragment
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Heading](heading/)(int) | Initierar en ny instans av Cell‑klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Hämtar textposition för text, representerad med [`TextFragment`](../../aspose.pdf.text/textfragment/) objekt. YIndent i Position‑strukturen representerar baslinjekoordinationen för textfragmentet. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Hämtar destination Page. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Hämtar eller anger paragrafens slutnot.(endast för pdf-generering) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Hämtar eller anger paragrafens fotnot.(endast för pdf-generering) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Hämtar formulärobjektet som innehåller TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Hämtar eller anger en horisontell justering av textfragmentet. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Anger fragmentets hyperlänk |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Hämtar om rubriken ska numreras automatiskt. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Hämtar om rubriken ska vara i toc‑listan. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Hämtar nivån. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Hämtar sidan som innehåller TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Hämtar eller anger textposition för text, representerad med [`TextFragment`](../../aspose.pdf.text/textfragment/) objekt. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Hämtar rektangeln för TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Hämtar alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts med kortare/längre text. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Hämtar textsegment för aktuell [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Hämtar rubrikens startnummer. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Hämtar eller anger stil. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Hämtar eller anger String‑textobjektet som [`TextFragment`](../../aspose.pdf.text/textfragment/)‑objektet representerar. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Hämtar eller anger alternativ för textredigering. Alternativen definierar särskilt beteende när begärt tecken inte kan skrivas med teckensnittet. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Hämtar eller anger texttillstånd för den text som [`TextFragment`](../../aspose.pdf.text/textfragment/)‑objektet representerar. |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Hämtar Page som innehåller denna rubrik. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Hämtar den övre Y‑koordinaten för dessa rubriker. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Hämtar eller anger användarlabel. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering av textfragmentet. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Hämtar eller anger antal radbrytningar för detta stycke (endast för PDF‑generering). |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Klona rubriken. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Klona rubriken med alla segment. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Hämtar [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) som representerar den angivna delen av [`TextFragment`](../../aspose.pdf.text/textfragment/) texten. |

### Se även

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


