---
title: Class TrimMarkAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.TrimMarkAnnotation klass. Representerar en Trim Mark-anteckning
type: docs
weight: 2690
url: /sv/net/aspose.pdf.annotations/trimmarkannotation/
---
## TrimMarkAnnotation klass

Representerar en Trim Mark-anteckning.

```csharp
public sealed class TrimMarkAnnotation : CornerPrinterMarkAnnotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TrimMarkAnnotation](trimmarkannotation/)(Page, PrinterMarkCornerPosition) | Initierar en ny instans av `TrimMarkAnnotation` klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över anteckningsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in aktuell anteckningsutseende tillstånd. |
| override [AnnotationType](../../aspose.pdf.annotations/trimmarkannotation/annotationtype/) { get; } | Hämtar typ av anteckning. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendediktionären för anteckningen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in anteckningens kantkarakteristika. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar anteckningens egenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in anteckningens färg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in anteckningens text. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för anteckningen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar det fullständigt kvalificerade namnet på anteckningen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjden på anteckningen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när anteckningen senast ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in anteckningens namn på sidan. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Hämtar index för sidan som innehåller anteckningen. |
| [Position](../../aspose.pdf.annotations/cornerprintermarkannotation/position/) { get; set; } | Hämtar eller ställer in positionen för märket på sidan. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller ställer in anteckningens rektangel. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendediktionären för anteckningen. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjustering för anteckningen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på anteckningen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som indikerar Z-ordningen för grafiken. En grafik med större ZIndex kommer att placeras över grafiken med mindre ZIndex. ZIndex kan vara negativ. Grafik med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/trimmarkannotation/accept/)(AnnotationSelector) | Accepterar besökare för anteckningsbehandling. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matristransformeringen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Återger alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placera anteckningens innehåll direkt på sidan, anteckningsobjektet kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för anteckningen med hänsyn till sidrotation. |

## Anmärkningar

Trimmärken placeras i hörnen av en tryckt sida för att indikera var sidan ska trimmas.

### Se Även

* klass [CornerPrinterMarkAnnotation](../cornerprintermarkannotation/)
* namnrymd [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* sammansättning [Aspose.PDF](../../)