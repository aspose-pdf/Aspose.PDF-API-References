---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Heading klass. Representerar rubrik
type: docs
weight: 5470
url: /sv/net/aspose.pdf/heading/
---
## Rubrikklass

Representerar rubrik.

```csharp
public sealed class Heading : TextFragment
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Heading](heading/)(int) | Initierar en ny instans av Cell-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Hämtar textposition för text, representerad med [`TextFragment`](../../aspose.pdf.text/textfragment/) objekt. YIndent i Position-strukturen representerar baslinjekoordinaten för textfragmentet. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Hämtar destinationssidan. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Hämtar eller ställer in styckets slutnot. (endast för pdf-generering) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Hämtar eller ställer in styckets fotnot. (endast för pdf-generering) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Hämtar formulärobjektet som innehåller TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Hämtar eller ställer in en horisontell justering av textfragmentet. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Ställer in fragmentets hyperlänk |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Hämtar om rubriken ska numreras automatiskt. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om stycket är inline. Standard är falskt. (för pdf-generering) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Hämtar om rubriken ska vara i innehållsförteckningen. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Hämtar nivån. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Hämtar sidan som innehåller TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Hämtar eller ställer in textpositionen för text, representerad med [`TextFragment`](../../aspose.pdf.text/textfragment/) objekt. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Hämtar rektangeln för TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Hämtar textersättningsalternativ. Alternativen definierar beteendet när fragmenttexten ersätts med kortare/längre. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Hämtar textsegment för det aktuella [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Hämtar rubrikens startnummer. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Hämtar eller ställer in stil. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Hämtar eller ställer in strängtextobjektet som [`TextFragment`](../../aspose.pdf.text/textfragment/) objektet representerar. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Hämtar eller ställer in textredigeringsalternativ. Alternativen definierar speciellt beteende när begärd symbol inte kan skrivas med teckensnitt. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Hämtar eller ställer in texttillståndet för den text som [`TextFragment`](../../aspose.pdf.text/textfragment/) objektet representerar. |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Hämtar sidan som innehåller denna rubrik. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Hämtar den övre Y för dessa rubriker. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Hämtar eller ställer in användarens etikett. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av textfragmentet. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Hämtar eller ställer in antalet omslag för detta stycke (endast för pdf-generering) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Klona rubriken. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Klona rubriken med alla segment. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Hämtar [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) som representerar angiven del av texten i [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### Se Även

* klass [TextFragment](../../aspose.pdf.text/textfragment/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)